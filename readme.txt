Set-ExecutionPolicy RemoteSigned -Scope LocalMachine

npm create vite@latest .
npm init -y
npm i express mongoose dotenv jsonwebtoken bcryptjs cookie-parser cloudinary socket.io
npm i nodemon -D
npm run dev