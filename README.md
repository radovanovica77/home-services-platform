Majstorija — Home Services Platform

![Majstorija Logo](logo.png)

A web platform connecting users with local tradespeople and service providers in Serbia.
Built as a team project by three Computer Science students.

Team
- Aleksandar Radovanović
- Stefan Filipović  
- Mihajlo Antić

Features
- User and worker registration & login
- Browse and book home services
- Worker dashboard for managing orders
- User dashboard for tracking requests
- Profile editing and password management
- JWT-based authentication
- Payment integration (Stripe)

Tech Stack
**Backend**
- ASP.NET Core Web API
- ADO.NET + SQL Server
- JWT Authentication + BCrypt
- Layered architecture (API → Business Layer → DAL)

**Frontend**
- React + Vite
- Tailwind CSS
- React Router DOM

Getting Started

### Frontend
```bash
cd frontend
npm install
npm run dev
```

### Backend
1. Open `backend/` in Visual Studio
2. Create `appsettings.json` with your connection string
3. Run the API

> ⚠️ `appsettings.json` is not included in the repository. You must create it locally.

## 📄 License

This project was created for educational purposes.
