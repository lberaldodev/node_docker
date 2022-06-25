<h1 align="center">Welcome to Nodejs with Docker 👋</h1>
<p>
  <img alt="Version" src="https://img.shields.io/badge/version-1.0.0-blue.svg?cacheSeconds=2592000" />
  <a href="https://github.com/lberaldodev/node_docker/blob/master/readme.md" target="_blank">
    <img alt="Documentation" src="https://img.shields.io/badge/documentation-yes-brightgreen.svg" />
  </a>
  <a href="#" target="_blank">
    <img alt="License: ISC" src="https://img.shields.io/badge/License-ISC-yellow.svg" />
  </a>
</p>

> Simple NodeJS example with dockerfile and hot reload using nodemon

### 🏠 [Homepage](https://github.com/lberaldodev/node_docker)

## Create your image

```sh
docker build -t nodejs .
```

## Execute and expose port 3000

```sh
docker run -it --name nodejs -v $(pwd):/var/www/node -p 3000:3000 nodejs 
```

## Author

👤 **Lucas da Silva Beraldo**

* Github: [@lberaldodev](https://github.com/lberaldodev)

## Show your support

Give a ⭐️ if this project helped you!

***
_This README was generated with ❤️ by [readme-md-generator](https://github.com/kefranabg/readme-md-generator)_