event-sourcing-bundle
=====================

A Symfony project created on February 27, 2016, 7:42 pm.

[![Codacy Badge](https://api.codacy.com/project/badge/grade/c8c71b8095304e18a6e25ad580b485fa)](https://www.codacy.com/app/rojoangel/event-sourcing-bundle)

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
