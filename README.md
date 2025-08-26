# MERN-chatWeb

A lightweight web-based chat application (similar to **ProtectedText** or **Google Meet-style temporary rooms**) built with the **MERN stack**.  
This project is currently **under active development** 馃毀.

---

## 🚀 Features (Planned / In Progress)

- **Temporary Chat Rooms**  
  - Users can chat instantly by sharing a unique link.  
  - No login or registration required.  

- **Custom Expiry**  
  - Rooms and chat history auto-expire after a configurable time limit.  

- **MERN Stack**  
  - **MongoDB** – for temporary message storage.  
  - **Express.js** – backend API and routing.  
  - **React.js** – clean and minimal chat interface.  
  - **Node.js** – server environment.  

- **Privacy Focused**  
  - No permanent storage of messages.  
  - All rooms are temporary.  

---

## 📦 Installation (Development Mode)

1. **Clone the repository**
   ```bash
   git clone https://github.com/mjtech46/MERN-chatWeb.git
   cd MERN-chatWeb
   ```

2. **Backend Setup**
   ```bash
   cd server
   npm install
   npm run dev
   ```
   - Server runs on: `http://localhost:5000`

3. **Frontend Setup**
   ```bash
   cd client
   npm install
   npm start
   ```
   - React app runs on: `http://localhost:3000`

---

## 🛠️ Roadmap

- [ ] Create / Join chat rooms using unique links  
- [ ] Set custom expiry for rooms  
- [ ] Auto-delete expired rooms/messages  
- [ ] Add support for emojis / markdown  
- [ ] Add optional end-to-end encryption  

---

## 🤝 Contributing

This project is in **early development**.  
Contributions, ideas, and suggestions are welcome. Feel free to open an issue or PR!

---

## 📜 License

MIT License. Free to use and modify.
