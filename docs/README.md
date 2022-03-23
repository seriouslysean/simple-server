# Simple Server

## Start Server

- Run `npm ci` to install deps
- Run `npm start` to start the server

## View on iPhone

Once the server is running, you can view it on your iPhone relatively easily.

- Plug your iPhone in to your computer via USB
- Ensure the server is running on `http://localhost:3000`
- Open System Preferences > Sharing
- Copy your computer's network name (e.g. `gizmocluster.local`)
- Enable Internet Sharing via the iPhone USB interface
- Open your computer's name and port on your iPhone browser (e.g. `gizmocluster.local:3000`)

| Internet Sharing | Mac | iPhone |
| ---------------- | --- | ------ |
| ![Internet Sharing](./internet-sharing.png) | ![Mac Server](./mac-server.png) | ![iOS Server](./ios-server.png) |

## Packages

- [Lite Server](https://www.npmjs.com/package/lite-server)
