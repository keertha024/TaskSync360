# 🔄 taskSync360  
*A Real-Time Collaborative Todo App with Social Login*  
**🚀 Built for the Katomaran Fullstack Hackathon**  

![Architecture Diagram](./assets/architecture-diagram.png)  
*(System architecture overview - React frontend, Node.js backend, and Supabase database)*  

---

## 🚀 Features  
- **OAuth 2.0 Login** (Google/GitHub) with JWT sessions  
- **Real-time updates** via WebSockets (Socket.io)  
- **Task Collaboration**: Share tasks via email/username  
- **Smart Filters**: Due today/overdue/by priority  
- **Offline Support**: Basic task caching  
- **Toast Notifications**: For user actions  

---

## 🛠 Tech Stack  
| **Frontend**       | **Backend**        | **Database**     | **DevOps**       |  
|--------------------|--------------------|------------------|------------------|  
| React 18           | Node.js (Express)  | Supabase         | Vercel           |  
| Socket.io Client   | RESTful API        | PostgreSQL       | Railway          |  
| Tailwind CSS       | JWT Auth           | Realtime API     | GitHub Actions   |  

---

## 📦 Setup (Local Development)  
```bash
# 1. Clone repository
git clone https://github.com/your-username/taskSync360.git

# 2. Setup backend
cd server
npm install
cp .env.example .env  # Add your Supabase/Google OAuth keys
npm run dev

# 3. Setup frontend
cd ../client
npm install
npm start
