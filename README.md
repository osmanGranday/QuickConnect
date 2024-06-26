# QuickConnect
Initialize npm and Install Dependencies:

npm init -y
npm install ws

Start the Signaling Server:
node server/server.js

Start a Local HTTP Server to Serve the Client Files:

npx http-server client -p 8081
