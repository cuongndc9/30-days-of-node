# Mern Stack Starter

> 🗡️🍣 Getting Started with MERN Stack.

## Install

Install dependencies
```
$ npm install && npm run client-install
```
Create `.env` file
```
MONGODB_URI=<Your Mongodb URI>
```

## Usage

Run `server` only
```
$ npm start
```
Run `client` only
```
$ npm run client
```
Run `client` & `server`
```
$ npm run dev
```

## API

| Route            | HTTP method | Description                 |
|------------------|-------------|-----------------------------|
| /api/cats        | `GET`       | Get all the cats.           |
| /api/cats        | `POST`      | Create a cat.               |
| /api/cats/:catId | `GET`       | Get a single cat.           |
| /api/cats/:catId | `PUT`       | Update a cat with new info. |
| /api/cats/:catId | `DELETE`    | Delete a cat.               |

## License

![License](https://img.shields.io/github/license/cuongw/mern-stack-starter.svg?style=flat-square)

<!-- INSPIRATIONAL_QUOTE_START -->
> "Don't be afraid to give up the good to go for the great." - John D. Rockefeller
<!-- INSPIRATIONAL_QUOTE_END -->
