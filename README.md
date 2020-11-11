# Cashbox Application 

I created this application because my girlfriend and me needed a digital *cash box*. Before COVID-19 we had an analog box to store cash every month. With this money we bought groceries or went out to eat. Since everybody now uses contactless payment the old approach is useless.

## Setup local environment

### Installation

In the backend:

Generate secret key `php artisan jwt:secret`

Copy and adapt environment file `cp .env.template .env`


### Start servers

Start backend server: `php -S localhost:8080 -t public`

Start frontend server: `ng serve --open`
