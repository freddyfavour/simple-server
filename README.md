# simpleServer

**simpleServer** is a basic HTTP server created using Node.js. It serves an HTML file (`index.html`) when accessed through a web browser. This project is ideal for beginners looking to understand how to set up a server in Node.js.

## Features

- Serves static HTML content.
- Easy to set up and run.
- Built with core Node.js modules: `http` and `fs`.

## Prerequisites

- [Node.js](https://nodejs.org/) installed on your machine (version 12 or higher recommended).

## Getting Started

Follow these steps to set up and run the server:

1. **Clone the Repository**
   ```bash
   git clone https://github.com/freddyfavour/simple-server.git
   cd simpleServer
   ```

2. **Install Dependencies**
   - There are no additional dependencies for this simple server, but ensure you have Node.js installed.

3. **Create Your HTML File**
   - Ensure that you have an `index.html` file in the same directory as your server script. You can use the following example:
     ```html
     <!DOCTYPE html>
     <html lang="en">
     <head>
         <meta charset="UTF-8">
         <meta name="viewport" content="width=device-width, initial-scale=1.0">
         <title>My Simple Server</title>
     </head>
     <body>
         <h1>Welcome to My Simple Node.js Server!</h1>
         <p>This is served from index.html.</p>
     </body>
     </html>
     ```

4. **Run the Server**
   ```bash
   node simpleServer.js
   ```

5. **Access the Server**
   - Open your web browser and navigate to `http://localhost:3000`. You should see the contents of your `index.html` file displayed.

## Usage

You can modify the `index.html` file to change the content served by your server. Feel free to experiment with different HTML elements and styles!

## Contributing

Contributions are welcome! If you have suggestions or improvements, please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
