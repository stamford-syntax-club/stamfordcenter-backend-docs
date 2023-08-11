---
sidebar_position: 1
slug: /
---

# Introduction 👋

Welcome to the documentation of our [stamford center's](https://center.stamford.dev) backend service!

## Description 📝

The ssc-backend is designed to serve as a scalable backend for various applications. It's implemented using Express for handling HTTP requests and has built-in support for S3, MongoDB, and more. The code is written in TypeScript, and the application can be built and run using Docker.

## Features ✨

- **Self-hosted S3 Integration** 💼: Seamlessly interact with our own instance of an S3 service.
- **MongoDB Support** 🍃: Leverage MongoDB as the underlying database.
- **CORS Support** 🌐: Built-in support for Cross-Origin Resource Sharing (CORS).
- **Environment Configuration** 🌲: Utilize `dotenv` for managing environment variables.
- **Development Tools** 🔧: Includes a development environment with hot-reloading using `concurrently`, `nodemon`, and TypeScript.

## Prerequisites 🛠️

- [Node.js](https://nodejs.org) (version as defined in Dockerfile, recommended Alpine variant) 📦
- [Docker](https://www.docker.com/) 🐳

## Installation 🖥️

1. **Clone the Repository** 📂
   ```
   git clone https://github.com/your-username/ssc-backend.git
   cd ssc-backend
   ```

2. **Build the Docker Image** 🏗️
   ```
   docker build -t ssc-backend .
   ```

3. **Run the Docker Container** 🚀
   ```
   docker run -p 8080:8080 ssc-backend
   ```

The application will be available at `http://localhost:8080`.

## Development 💻

To start the development server with hot-reloading:

```
npm run dev
```

## Scripts 🧰

- `npm run build`: Compile TypeScript files.
- `npm start`: Start the production server.
- `npm run dev`: Start the development server.

## License 📄

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Author 👤
- **Tawan Tocharoentanaphol** - [@Lxkas](https://github.com/Lxkas)
- **Chinathai Panditya** - [@chinathaip](https://github.com/chinathaip)