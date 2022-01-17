# E-CommerceBackEnd

![Github licence](http://img.shields.io/badge/license-MIT-blue.svg)

## Table Of Content

- [General Info](#generalinfo)
- [Technologies](#technologies)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Questions](#questions)

## General Info

We’ll take a working Express.js API and configure it to use Sequelize to interact with a MySQL database. This application won’t be deployed so i’ll show a walkthrough video that demonstrates its functionality.
Image showcasing the application running in Postman. (https://watch.screencastify.com/v/537Z0f3NSNX2hRzpuCyV)

Video:

## Technologies

Project is created with

- `Javascript`
- `Node.js`
- `Sequelize`
- `MySQL2`
- `Express`
- `Dotenv`
- `Installation`

To get started first clone this repository.
Both Node.js and MySQL must be installed on your computer.

## Install dependencies

```bash
- npm init --y

- npm install express sequelize mysql2
```

Open up MySQL shell and input

```bash
db/schema.sql
```

and

```bash
use ecommerce_db
```

Then quit MySQL shell and input the following in your terminal

```bash
npm run seed
```

to start running application simply input

```bash
npm start
```

Open up Insomnia core to GET, POST, PUT and DELETE from different routes.

## Usage

The application is used to GET data for each route(categories, products, or tags) as well as create, update, and delete data in those routes.

## License

This repository is licensed under the MIT license.

## Questions

Questions about this repository? Please contact me at elmira.tashvighi@gmail.com. View more of my work in GitHub at Elmiratash

```

```
