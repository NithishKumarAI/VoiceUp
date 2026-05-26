# VoiceUp

AI-powered citizen grievance and complaint management platform built using Node.js, Express, MongoDB, and Google Gemini APIs.

VoiceUp enables citizens to file and track civic complaints related to infrastructure, sanitation, electricity, water supply, roads, and other public services through a centralized web portal. The system includes role-based dashboards for citizens, officers, and administrators, along with AI-assisted complaint categorization and government scheme recommendations.

---

## Features

### Citizen Portal
- User registration and login
- File complaints with location details
- Public complaint tracking using tracking ID
- View personal complaint history
- AI-powered support chatbot
- Multilingual support using Google Translate

### Officer Dashboard
- View assigned complaints
- Update complaint status
- Manage complaint workflows
- Email notifications for status updates

### Admin Dashboard
- Create and manage officers
- Assign complaints manually
- View complaint analytics
- Monitor platform activity using Chart.js dashboards

---

## AI Features

Integrated Google Gemini APIs for:

- Automatic complaint categorization
- Government scheme recommendations
- AI assistant chatbot for user guidance

---

## Tech Stack

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose

### Frontend
- EJS Templates
- HTML/CSS/JavaScript
- Chart.js

### Authentication
- JWT Authentication
- bcrypt Password Hashing

### AI & APIs
- Google Gemini API
- Nodemailer
- CountryStateCity API

### Deployment
- Vercel

---

## Architecture

```text
User → EJS Frontend → Express Backend → MongoDB
                                ↓
                         Google Gemini API
```

---

## Complaint Workflow

```text
Citizen submits complaint
        ↓
Gemini categorizes complaint
        ↓
System assigns officer
        ↓
Tracking ID generated
        ↓
Officer updates status
        ↓
Citizen receives email notification
```

---

## Project Structure

```text
VoiceUp/
│
├── model/
├── public/
├── utils/
├── views/
├── images/
├── app.js
├── package.json
└── vercel.json
```

---

## Learning Outcomes

This project helped develop practical understanding of:

- Full-stack web development
- Authentication and role-based access control
- MongoDB schema design
- AI workflow integration using Gemini APIs
- Server-side rendering with EJS
- Deployment using Vercel
- RESTful routing and backend architecture
- Email notification systems

---

## Future Improvements

Potential enhancements:

- Voice input support using speech recognition
- RAG-based government scheme retrieval
- Real-time complaint updates using WebSockets
- Modern frontend migration (React / Next.js)
- Better observability and logging
- Improved security and environment management

---

## Disclaimer

This project was built for learning and portfolio purposes and is not connected to any real government grievance platform.
