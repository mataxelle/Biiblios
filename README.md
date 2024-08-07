# Biiblios

## Table of contents

- [General info](#general-info)
- [Features](#features)
- [Development environment](#development-environment)
- [Install on local](#install-on-local)

## General info

Project : A CRUD project, with admin registration, book, author and editor list for partage. Include admin gestion.

## Features

### Front : users access

- Homepage : display book list button.
- Register / login page for administration
- Create / Edit book, author, editor form
- Book, author and editor page

### Back : admin access

- Admin / user pages : includes all CRUD actions

## Development environment

- PHP 8.2
- Node 18.14.2 et npm
- Symfony CLI
- Composer

## Requirements check

- symfony check:requirements

## Install on local

1. Clone the repo on your local webserver : [Repository](https://github.com/mataxelle/Biiblios.git).

2. Make sure you have Php and composer on your computer.

3. Create a database.

## Add Fixtures tests

```
symfony console doctrine:fixtures:load
```

### Start the environment

```
Composer install
npm install
npm run build
symfony server:start
```
