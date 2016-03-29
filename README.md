event-sourcing-bundle
=====================

A Symfony project created on February 27, 2016, 7:42 pm.

[![Build Status](https://travis-ci.org/rojoangel-toyprojects/event-sourcing-app.svg?branch=master)](https://travis-ci.org/rojoangel-toyprojects/event-sourcing-app)
[![Codacy Badge](https://api.codacy.com/project/badge/grade/d48e0647918f4d31a48db432de1899a2)](https://www.codacy.com/app/rojoangel/event-sourcing-app)
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
