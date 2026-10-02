# 🎵 Spotify Clone

A modern **Spotify Clone** built with **HTML, CSS, JavaScript, Tailwind CSS, and Vite**.
The project recreates the core Spotify experience with a responsive music dashboard, authentication UI, playlists, search, and music-related functionality.

> **Note:** This project is created for educational and portfolio purposes and is not affiliated with Spotify.

---

## ✨ Features

* 🎧 Spotify-inspired music interface
* 🔐 Login / Authentication UI
* 🏠 Music dashboard
* 🔎 Search songs, artists and albums
* 🎵 Music playback interface
* ⏮️ Previous / Next / Play / Pause controls
* ❤️ Favorites
* 📚 Playlist management
* 📱 Responsive design
* 🌙 Spotify-inspired dark UI
* ⚡ Fast Vite development environment
* 🎨 Tailwind CSS styling
* 🔗 Spotify Developer API integration

---

## 🛠️ Tech Stack

| Technology      | Usage                    |
| --------------- | ------------------------ |
| HTML5           | Application structure    |
| CSS3            | Styling                  |
| JavaScript      | Application logic        |
| Tailwind CSS    | UI styling               |
| Vite            | Development & build tool |
| Spotify Web API | Music data               |

---

## 📂 Project Structure

```text
clone-music/
│
├── src/
│   ├── assets/
│   ├── components/
│   ├── pages/
│   └── ...
│
├── .gitignore
├── package.json
├── package-lock.json
├── postcss.config.cjs
├── tailwind.config.cjs
├── vite.config.js
└── README.md
```

---

## 🚀 Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/adarshshukla112233445566-ux/clone-music.git
```

### 2. Enter the project

```bash
cd clone-music
```

### 3. Install dependencies

```bash
npm install
```

### 4. Start the development server

```bash
npm run dev
```

Vite will provide the local development URL in the terminal, normally:

```text
http://localhost:5173
```

---

## 🔑 Spotify API Configuration

If the application uses Spotify API credentials, create a `.env` file in the project root.

```env
VITE_CLIENT_ID=YOUR_SPOTIFY_CLIENT_ID
```

Never commit your real API credentials to GitHub.

Make sure `.env` is included in `.gitignore`.

---

## 🏗️ Production Build

Create a production build with:

```bash
npm run build
```

Preview the production build locally:

```bash
npm run preview
```

The production files will be generated inside:

```text
dist/
```

---

## ☁️ Deploy on Vercel

This project is compatible with **Vercel**.

### Vercel Configuration

```text
Framework Preset: Vite
Build Command: npm run build
Output Directory: dist
Install Command: npm install
```

You **do not need to run `npm install` on your PC** just to deploy through GitHub → Vercel. Vercel installs the dependencies on its build server.

---

## 🎯 Project Goals

The goal of this project is to recreate the core user experience of a modern music streaming platform while practicing:

* Frontend development
* Responsive UI design
* JavaScript application logic
* REST API integration
* Authentication flows
* Playlist management
* Modern build tools
* Deployment workflows

---

## 👨‍💻 Author

**Adarsh Shukla**

GitHub:
https://github.com/adarshshukla112233445566-ux

Repository:
https://github.com/adarshshukla112233445566-ux/clone-music

---

## ⚠️ Disclaimer

Spotify is a trademark of Spotify AB.

This project is an independent educational project created for learning and portfolio purposes. It is not an official Spotify product.

---

## 📄 License

This project is intended for educational and portfolio purposes.
