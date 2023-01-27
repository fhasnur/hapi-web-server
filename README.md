# Hapi Web Server

Simple Web Server built using Hapi Node.js Framework

## Running Locally

1. Clone the source code

```
git clone https://github.com/fhasnur/hapi-web-server.git
```

2. Install development dependencies

```
npm install
```

3. Run a local development server

```
npm run start
```

Hapi Web Server is now running, and can be accessed by pointing a web at [http://localhost:5000/](http://localhost:5000/)

## Example Requests

Try to request using the command line

```cmd
curl -X GET http://localhost:5000
// output: Homepage

curl -X GET http://localhost:5000/about
// output: About page

curl -X GET http://localhost:5000/test
// output: Halaman tidak ditemukan

curl -X POST http://localhost:5000
// output: Halaman tidak dapat diakses dengan method tersebut

curl -X GET http://localhost:5000/hello/dicoding
// output: Hello, dicoding!

curl -X GET http://localhost:5000/hello
// output: Hello, stranger!

curl -X GET http://localhost:5000/hello/dicoding?lang=id
// output: Hai, dicoding!

curl -X GET http://localhost:5000/hello/dicoding
// output: Hello, dicoding!
```
