# ZfcAdmin Module for Zend Framework 2

Version 0.0.1 Created by [Jurian Sluiman](http://juriansluiman.nl/en/) and [Martin Shwalbe](https://github.com/Hounddog)

## Introduction

soon to come

## Installation

### Main Setup

1. Clone this project into your `./vendor/` directory and enable it in your
   `application.config.php` file.

## Usage
soon to come

## Enable Access restriction

Restrict access to unauthorized Userd.

### Solution

1. Install BjyAuthorize and enable in you application.config.php
2. Import data/data.sql into your database.
3. Create a user with ZfcUser and set the user_id and role_id in the database
    (e.g. user_d = 1, role_id = admin)
    
## How To override Admin Layout

Override the built in admin layout with your custom layout

### Solution

1. In your module under the `view` directory create the folder `layout`
2. Create the override script `admin.phtml`

## How to override Admin controller view

Override the built in Controller view

### Solution

1. In your module, under the view directory, create the folder tree zfc-admin/admin
2. Create the necessary override view scripts, depending on which page(s) you want to change:
    * Default page: zfc-admin/admin/index.phtml


NOTE: Your module must be loaded after ZfcAdmin or the overriding will not work.  To do this, place your module after ZfcAdmin in the `modules` key of your application configuration (`config/application.config.php`).

