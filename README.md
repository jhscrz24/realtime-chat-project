# Chizmisify - A Realtime Chat App

![Demo App](/frontend/public/screenshot-for-readme.png)

![Demo App2](/frontend/public/screenshot-for-readme2.png)

![Demo App3](/frontend/public/screenshot-for-readme3.png)

Highlights:

- Tech stack: MERN (MongoDB, Express, React, Node.js) combined with Socket.io, TailwindCSS, and DaisyUI
- Implements authentication and authorization using JWT
- Real-time chat functionality powered by Socket.io
- Displays online/offline user status
- Offers 32 customizable color themes using DaisyUI
- Global state management with Zustand
- Cron Package for Free Plan if Deploying

### Setup .env file

```js
MONGODB_URI=...
PORT=5001
JWT_SECRET=...

CLOUDINARY_CLOUD_NAME=...
CLOUDINARY_API_KEY=...
CLOUDINARY_API_SECRET=...

NODE_ENV=development
```

### Build the app

```shell
npm run build
```

### Start the app

```shell
npm start
```
