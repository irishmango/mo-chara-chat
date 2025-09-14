# Mo Chara Chat  

Mo Chara Chat is a full-stack real-time chat platform built on the **MERN stack** (MongoDB, Express, React, Node.js). It offers a sleek interface, secure authentication, and seamless messaging.

![Login Page](./images/snappy_login.png)  
![Home Page](./images/snappy.png)  

---

## ✨ Features
- Real-time messaging with WebSockets  
- Secure login and user authentication  
- Responsive and modern UI design  
- Built with the MERN stack  
- Simple setup locally or via Docker  

---

## ⚙️ Requirements
Before starting, ensure you have:
- [Node.js](https://nodejs.org/en/download)  
- [MongoDB](https://www.mongodb.com/docs/manual/administration/install-community/)  

Make sure MongoDB is running either locally or in Docker before launching the app.

---

## 🚀 Getting Started

### Local Setup

1. **Clone the repository**  
   ```bash
   git clone <your-repo-url>
   cd mo-chara-chat
   ```

2. **Set up environment variables**  
   Rename example files to `.env`:  
   ```bash
   cd public && mv .env.example .env && cd ..
   cd server && mv .env.example .env && cd ..
   ```

3. **Install dependencies**  
   ```bash
   cd server && yarn && cd ..
   cd public && yarn && cd ..
   ```

4. **Start the servers**  
   Open two terminals and run the commands separately:  

   - Frontend  
     ```bash
     cd public
     yarn start
     ```  

   - Backend  
     ```bash
     cd server
     yarn start
     ```  

5. Open [http://localhost:3000](http://localhost:3000) in your browser.

---

### Using Docker

1. Ensure **Docker** and **Docker Compose** are installed.  
2. Build the containers:  
   ```bash
   docker compose build --no-cache
   ```  
3. Start the containers:  
   ```bash
   docker compose up
   ```  
4. Access the app at [http://localhost:3000](http://localhost:3000).

---

## 📝 License
This project is intended for learning and demonstration.  
Feel free to modify and expand it as you wish.
