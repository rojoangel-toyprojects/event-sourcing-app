event-sourcing-bundle
=====================

A Symfony project created on February 27, 2016, 7:42 pm.

## How to install the application
After cloning this repository run
```
composer install
# create event-store database
bin/console doctrine:database:create
# create event-store schema
bin/console broadway:event-store:schema:init
# start server
bin/console server:start
# create a payment
bin/console create-payment
```
