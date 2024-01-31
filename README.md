

# Text Editor

## Overview
This repository contains the source code for a command-line-based text editor application. Leveraging Node.js, Express, and MongoDB, this application offers a robust platform for creating and managing text documents. Key features include data persistence via IndexedDB, service worker implementation for offline functionality, and the ability to bundle JavaScript files using Webpack.

## Features

- **Client-Server Architecture**: Upon launching, users are greeted with a well-organized folder structure separating client and server logic.
- **Quick Start**: Executing `npm run start` in the root directory boots up both the backend services and the client-facing interface.
- **Webpack Integration**: JavaScript files are efficiently bundled, ensuring a streamlined development process and faster load times.
- **Modern JavaScript Support**: The application seamlessly handles next-gen JavaScript, thanks to Babel integration, ensuring compatibility across browsers.
- **Persistent Data Storage**: Utilizes IndexedDB for local data storage, enabling content preservation across sessions.
- **PWA Capabilities**:
  - The app can be installed on the desktop, appearing as a native application icon for quick access.
  - Service workers, managed through Workbox, provide offline functionality and resource caching.
- **Deployment Ready**: Includes configured build scripts for Webpack, facilitating easy deployment to platforms like Render.

## Getting Started

### Prerequisites
- Node.js
- MongoDB

### Installation
1. Clone the repository:
   ```
   git clone https://github.com/CaveManEN/text-editor.git
   ```
2. Navigate to the project directory and install dependencies:
   ```
   cd text-editor
   npm install
   ```
3. Start the application:
   ```
   npm run start
   ```

## Usage

Access the text editor through your browser by navigating to `localhost` with the port specified in your terminal after starting the application. For detailed functionality and additional commands, refer to the application documentation within the repository.





