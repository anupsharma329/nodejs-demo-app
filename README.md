# nodejs-demo-app

This is a simple Node.js demo application using Express.

## Project Structure

- `index.js`: Main application file. Starts an Express server and serves a basic route.
- `package.json`: Project metadata and dependencies.
- `Dockerfile`: Containerizes the app for easy deployment.

## Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) (v18 or above recommended)
- [npm](https://www.npmjs.com/)

### Installation
1. Clone the repository:
   ```sh
   git clone <repo-url>
   cd nodejs-demo-app
   ```
2. Install dependencies:
   ```sh
   npm install
   ```

### Running the App
```sh
node index.js
```
The app will run on [http://localhost:3000](http://localhost:3000).

## Docker

To build and run the app in a Docker container:

1. Build the Docker image:
   ```sh
   docker build -t nodejs-demo-app .
   ```
2. Run the Docker container:
   ```sh
   docker run -p 3000:3000 nodejs-demo-app
   ```

## API

- `GET /` — Returns a welcome message.

## License

ISC