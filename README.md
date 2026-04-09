# Vibe-Chat

Real-time fullstack chat application built with MERN, Socket.IO, TailwindCSS, DaisyUI, and Zustand.

## Features

- Secure authentication with JWT (HTTP-only cookies)
- One-to-one real-time messaging with Socket.IO
- Online users indicator
- Image messages and profile image upload via Cloudinary
- Protected routes for authenticated users
- Theme switcher with DaisyUI themes
- Zustand state management for auth, chat, and theme

## Tech Stack

- Frontend: React, Vite, TailwindCSS, DaisyUI, Zustand, Axios, Socket.IO Client
- Backend: Node.js, Express, MongoDB, Mongoose, JWT, Socket.IO
- Media: Cloudinary

## Project Structure

- backend: API, auth, DB models, Socket.IO server
- frontend: React app and UI components
- root package.json: helper scripts for build/start

## Environment Variables

Create backend/.env and set the following values:

- MONGODB_URI
- PORT
- JWT_SECRET
- CLOUDINARY_CLOUD_NAME
- CLOUDINARY_API_KEY
- CLOUDINARY_API_SECRET
- NODE_ENV

### Build the app

```shell
npm run build
```

### Start the app

```shell
npm start
```
