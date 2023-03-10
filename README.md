<h1 align='center'>
🚀 Mock Social Media Application - FakeBook
</h1>
<p align='center'>
MongoDB, ExpressJs, ReactJs, NodeJs
</p>

A social media application made with the MERN stack.

# 💻 Getting Started

Cloning the repository

```bash
$ git clone https://github.com/bygo7/FakeBook.git

$ cd pp-mern-social-media
```

## 💽 How to Run

To run the application without using docker. Run your MongoDB service

```bash
$ sudo service mongodb start
```

Starting the server application

```bash
$ cd server
$ yarn install
$ yarn dev
```

Starting the client application

```bash
$ cd client
$ yarn install
$ yarn start
```

The ReactJs application will run on _http://localhost:3000_ and the Express application will run on _http://localhost:3001_

# 🛠 Tools & Packages

### Client-Side

| Package Name                            | Description                                                                | Version |
| --------------------------------------- | -------------------------------------------------------------------------- | ------- |
| [axios](https://github.com/axios/axios) | Promise based HTTP client for the browser and node.js                      | ^0.19.2 |
| [highlight.js](https://highlightjs.org/)                            | Syntax highlighting with language autodetection.                           | ^10.1.2 |
| [moment](https://momentjs.com)                                  | Parse, validate, manipulate, and display dates                             | ^2.27.0 |
| [react-feather](https://github.com/feathericons/react-feather)                           | React component for Feather icons                                          | ^2.0.8  |
| [react-highlight](https://github.com/akiran/react-highlight)                         | React component for syntax highlighting                                    | ^0.12.0 |
| [react-markdown](https://github.com/rexxars/react-markdown)                          | Renders Markdown as React components                                       | ^4.3.1  |
| [react-moment](https://github.com/headzoo/react-moment)                            | React component for the moment date library.                               | ^0.9.7  |
| [react-router-dom](https://github.com/ReactTraining/react-router)                        | DOM bindings for React Router                                              | ^5.2.0  |
| [tailwindcss](https://tailwindcss.com)                             | A utility-first CSS framework for rapidly building custom user interfaces. | ^1.5.2  |

### Server-Side

| Package Name         | Description                                                                     | Version |
| -------------------- | ------------------------------------------------------------------------------- | ------- |
| [joi](https://github.com/sideway/joi)            | Object schema validation                                                        | ^17.1.1 |
| [@typegoose/typegoose](https://typegoose.github.io/typegoose/) | Define Mongoose models using TypeScript classes                                 | ^7.3.0  |
| [bcrypt](https://github.com/kelektiv/node.bcrypt.js)               | A bcrypt library for NodeJS.                                                    | ^5.0.0  |
| [cors](https://github.com/expressjs/cors)                 | Node.js CORS middleware                                                         | ^2.8.5  |
| [dotenv](https://github.com/motdotla/dotenv)               | Loads environment variables from .env file                                      | ^8.2.0  |
| [express](http://expressjs.com/)              | Fast, unopinionated, minimalist web framework                                   | ^4.17.1 |
| [jsonwebtoken](https://github.com/auth0/node-jsonwebtoken)         | JSON Web Token implementation (symmetric and asymmetric)                        | ^8.5.1  |
| [mongoose](https://mongoosejs.com)             | Mongoose MongoDB ODM                                                            | 5.9.22  |
| [mongoose-paginate-v2](https://github.com/aravindnc/mongoose-paginate-v2) | A cursor based custom pagination library for Mongoose with customizable labels. | ^1.3.9  |
| [morgan](https://github.com/expressjs/morgan)               | HTTP request logger middleware for node.js                                      | ^1.10.0 |
| [slugify](https://github.com/simov/slugify)              | Slugifies a String                                                              | ^1.4.4  |
| [nodemon](https://nodemon.io)              | Simple monitor script for use during development of a node.js app.              | ^2.0.4  |
