FROM node:latest

WORKDIR /var/www/laravel

COPY ./laravel .

RUN npm install

RUN npm install @inertiajs/inertia @inertiajs/inertia-vue3 --save

RUN npm cache clean --force

ENTRYPOINT ["npm", "run", "dev"]

