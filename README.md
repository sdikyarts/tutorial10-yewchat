# YewChat

A real-time chat application built with Rust and the Yew framework.

## Project Structure

- `YewChat/` - Frontend application built with Rust and Yew
- `SimpleWebsocketServer/` - WebSocket server for real-time communication

## Prerequisites

- Rust (latest stable version)
- Node.js and npm
- wasm-pack

## Building and Running

### Frontend (YewChat)

1. Navigate to the YewChat directory:
   ```bash
   cd YewChat
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Build the project:
   ```bash
   wasm-pack build --target bundler --features wee_alloc
   npm run build
   ```

4. Start the development server:
   ```bash
   npm run start
   ```

### Backend (SimpleWebsocketServer)

1. Navigate to the SimpleWebsocketServer directory:
   ```bash
   cd SimpleWebsocketServer
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the server:
   ```bash
   npm start
   ```

## Features

- Real-time messaging using WebSocket
- Modern UI built with Yew framework
- Efficient WebAssembly-based frontend
- Scalable WebSocket server

## License

MIT 