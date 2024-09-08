
# P2P File Sharing Application

This project is a simple Peer-to-Peer (P2P) file-sharing application built using Node.js and Express with file upload capabilities powered by Multer. The application allows users to upload files to a local server, and provides a link to download or access the uploaded files. The project is lightweight and serves as a basic example of handling file uploads and managing static files.

## Table of Contents

- [Features](#features)
- [Project Structure](#project-structure)
- [Setup Instructions](#setup-instructions)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
  - [Running the Server](#running-the-server)
  - [Uploading Files](#uploading-files)
- [Technology Stack](#technology-stack)
- [Contributing](#contributing)
- [License](#license)

## Features

- **File Upload**: Users can upload files through the web interface.
- **File Storage**: Uploaded files are saved on the server in a structured directory.
- **Download Links**: After uploading, a URL is provided to download the file.
- **Static File Hosting**: The server hosts uploaded files for easy access and sharing.

## Project Structure

- **index.html**: Main HTML file containing the user interface for file upload.
- **script.js**: Client-side JavaScript to handle form submissions and interactions.
- **server.js**: Backend server code written in Node.js using Express, handling file uploads and static file serving.
- **package.json**: Defines project dependencies and scripts.
- **package-lock.json**: Automatically generated file ensuring consistent installation of dependencies.
- **logo_image.png**: Project logo (can be customized or changed).
- **uploads/**: (Auto-created) Directory where uploaded files are stored.

## Setup Instructions

### Prerequisites

Make sure you have the following installed on your machine:
- [Node.js](https://nodejs.org/en/download/) (v12.0.0 or higher)
- [npm](https://www.npmjs.com/get-npm)

### Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/VaibhavGoyal01/p2p-file-sharing.git
   cd p2p-file-sharing
   ```

2. **Install Dependencies**:
   Install the required Node.js packages by running:
   ```bash
   npm install
   ```

## Usage

### Running the Server

Start the server by executing the following command:
```bash
node server.js
```

This will start the Node.js server on `http://localhost:5500`. The server will serve the main interface at the root URL, and handle file uploads and static file serving.

### Uploading Files

1. Open your browser and navigate to `http://localhost:5500`.
2. Use the provided form to upload a file.
3. Once uploaded, the server will respond with a URL where the file can be accessed or downloaded.

## Technology Stack

- **Node.js**: JavaScript runtime for the server-side logic.
- **Express**: Web framework for handling HTTP requests and routing.
- **Multer**: Middleware for handling `multipart/form-data`, primarily used for file uploads.
- **HTML/CSS/JavaScript**: Client-side interface for user interaction and file uploads.

## Contributing

Contributions are welcome! If you would like to contribute to this project, feel free to fork the repository and submit a pull request with your changes. Please ensure that your contributions follow the project's code style and quality guidelines.

### Steps for contributing:

1. Fork the repository.
2. Create a new feature branch.
3. Make your changes.
4. Submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
