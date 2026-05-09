<div align="center">

<!-- BANNER GIF - Replace with your own banner if desired -->
<img src="https://readme-typing-svg.demolab.com?font=Cinzel+Decorative&size=40&duration=3000&pause=1000&color=E50914&center=true&vCenter=true&width=900&height=100&lines=%F0%9F%8E%AC+Movie+Magic;Online+Ticket+Booking+System" alt="Movie Magic Typing SVG" />

<br/>

![Movie Magic Banner](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=Movie%20Magic&fontSize=80&fontColor=fff&animation=fadeIn&fontAlignY=38&desc=Online%20Movie%20Ticket%20Booking%20System&descAlignY=62&descAlign=50)

<br/>

<!-- BADGES -->
[![Java](https://img.shields.io/badge/Java-17-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)](https://www.java.com)
[![Spring Boot](https://img.shields.io/badge/Spring_Boot-2.7+-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)](https://spring.io/projects/spring-boot)
[![React](https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://react.dev)
[![MySQL](https://img.shields.io/badge/MySQL-8.0-4479A1?style=for-the-badge&logo=mysql&logoColor=white)](https://www.mysql.com)
[![Razorpay](https://img.shields.io/badge/Razorpay-Payment-02042B?style=for-the-badge&logo=razorpay&logoColor=white)](https://razorpay.com)
[![Google Maps](https://img.shields.io/badge/Google_Maps-API-4285F4?style=for-the-badge&logo=googlemaps&logoColor=white)](https://developers.google.com/maps)
[![JWT](https://img.shields.io/badge/JWT-Security-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)](https://jwt.io)
[![License](https://img.shields.io/badge/License-MIT-red?style=for-the-badge)](LICENSE)

<br/>

> 🎬 **A full-stack cinema ticket booking platform** — discover movies, select seats in real-time, pay securely, and enjoy the show. Built with Java Spring Boot + React.js during internship at **Zidio Development**.

<br/>

[![GitHub stars](https://img.shields.io/github/stars/SunilRavi7/Movie-Magic---Online-Ticket-Booking-System?style=social)](https://github.com/SunilRavi7/Movie-Magic---Online-Ticket-Booking-System/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/SunilRavi7/Movie-Magic---Online-Ticket-Booking-System?style=social)](https://github.com/SunilRavi7/Movie-Magic---Online-Ticket-Booking-System/network/members)
[![GitHub issues](https://img.shields.io/github/issues/SunilRavi7/Movie-Magic---Online-Ticket-Booking-System?style=social)](https://github.com/SunilRavi7/Movie-Magic---Online-Ticket-Booking-System/issues)

</div>

---

## 📌 Table of Contents

- [✨ Overview](#-overview)
- [🖼️ Screenshots](#️-screenshots)
- [🏗️ System Architecture](#️-system-architecture)
- [🚀 Features](#-features)
- [🛠️ Tech Stack](#️-tech-stack)
- [⚙️ Installation & Setup](#️-installation--setup)
- [🔌 API Endpoints](#-api-endpoints)
- [👥 User Roles](#-user-roles)
- [📁 Project Structure](#-project-structure)
- [🤝 Contributing](#-contributing)
- [📬 Contact](#-contact)

---

## ✨ Overview

<div align="center">
<img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width="500"/>
</div>

<br/>

**Movie Magic** is a comprehensive **online movie ticket booking system** built as a full-stack web application during my internship at **Zidio Development** (2024–25). The platform connects **customers**, **theatre owners**, and **administrators** in a seamless digital cinema ecosystem.

The system enables:
- 🎥 Real-time movie discovery & seat selection
- 💳 Secure payment via Razorpay + Digital Wallet
- 🗺️ Google Maps–powered theatre discovery
- 📧 Automated email booking confirmations
- 🔐 Role-based access control with JWT authentication

---

## 🖼️ Screenshots

<div align="center">

### 🏠 1. Home Page
> *Discover the latest blockbusters and book your seats instantly*

<!-- 📸 SCREENSHOT 1 — Replace the placeholder below with your actual screenshot -->
```
[ ADD HOME PAGE SCREENSHOT HERE ]
Upload your screenshot and replace this block with:
![Home Page](./screenshots/homepage.png)
```

---

### 🎭 2. Theatre Dashboard
> *Theatre owners can manage movies, shows, screens & bookings from one panel*

<!-- 📸 SCREENSHOT 2 — Replace the placeholder below with your actual screenshot -->
```
[ ADD THEATRE DASHBOARD SCREENSHOT HERE ]
Upload your screenshot and replace this block with:
![Theatre Dashboard](./screenshots/theatre-dashboard.png)
```

---

### 💳 3. Razorpay Payment Integration
> *Secure, multi-method payment — UPI, Cards, Net Banking, Wallet & more*

<!-- 📸 SCREENSHOT 3 — Replace the placeholder below with your actual screenshot -->
```
[ ADD RAZORPAY PAYMENT SCREENSHOT HERE ]
Upload your screenshot and replace this block with:
![Razorpay Payment](./screenshots/razorpay.png)
```

---

### 🗺️ 4. Google Maps API Integration
> *Location-based theatre discovery with real-time interactive maps*

<!-- 📸 SCREENSHOT 4 — Replace the placeholder below with your actual screenshot -->
```
[ ADD GOOGLE MAPS SCREENSHOT HERE ]
Upload your screenshot and replace this block with:
![Google Maps Integration](./screenshots/google-maps.png)
```

---

### 🪑 5. Seat Arrangement / Selection
> *Visual seat picker with Premium, Gold & Platinum tiers — real-time availability*

<!-- 📸 SCREENSHOT 5 — Replace the placeholder below with your actual screenshot -->
```
[ ADD SEAT ARRANGEMENT SCREENSHOT HERE ]
Upload your screenshot and replace this block with:
![Seat Arrangement](./screenshots/seat-selection.png)
```

</div>

> 💡 **Tip:** Create a `/screenshots` folder in the root of this repo and drop in your images, then update the paths above.

---

## 🏗️ System Architecture

<div align="center">
<img src="https://user-images.githubusercontent.com/74038190/212284087-bbe7e430-757e-4901-90bf-4cd2ce3e1852.gif" width="100"/>
</div>

The application follows a **4-Tier Layered Architecture** with clean separation of concerns:

```
┌─────────────────────────────────────────────────────────────────┐
│                        CLIENT LAYER                             │
│              Web Browser (React.js) / Mobile App                │
└────────────────────────┬────────────────────────────────────────┘
                         │ HTTP/HTTPS
┌────────────────────────▼────────────────────────────────────────┐
│                     FRONTEND LAYER (React.js)                   │
│   User Booking UI │ Admin Panel │ Theatre Dashboard             │
│   Seat Selection  │ Payment Component │ Google Maps Component   │
└────────────────────────┬────────────────────────────────────────┘
                         │ REST API (JWT Auth)
┌────────────────────────▼────────────────────────────────────────┐
│                   BACKEND LAYER (Spring Boot)                   │
│  Controllers: Movie │ Booking │ Payment │ Theatre │ User │ Admin │
│  Services:    Movie │ Booking │ Payment │ Theatre │ Notification │
│  Security:    JWT + Spring Security │ BCrypt Password Encoding  │
└────────────────────────┬────────────────────────────────────────┘
                         │ JDBC / JPA
┌────────────────────────▼────────────────────────────────────────┐
│                    DATABASE LAYER (MySQL 8.0)                   │
│    Users │ Movies │ Theatres │ Shows │ Bookings │ Payments      │
└─────────────────────────────────────────────────────────────────┘
                         │
┌────────────────────────▼────────────────────────────────────────┐
│                    EXTERNAL SERVICES                            │
│   Razorpay API │ Google Maps API │ Gmail SMTP │ File Storage    │
└─────────────────────────────────────────────────────────────────┘
```

---

## 🚀 Features

<div align="center">
<img src="https://user-images.githubusercontent.com/74038190/216644497-1951db19-8f3d-4e44-ac08-8e9d7e0d94a7.gif" width="400"/>
</div>

<br/>

### 👤 Customer Features
| Feature | Description |
|---|---|
| 🎬 Movie Discovery | Browse, search & filter movies by genre, language, rating |
| 🗺️ Theatre Locator | Find nearby theatres using Google Maps with GPS |
| 🪑 Real-Time Seat Selection | Interactive visual seat map with live availability |
| 💳 Multi-Payment Support | Razorpay (UPI, Cards, EMI, NetBanking) + Digital Wallet |
| 💰 Digital Wallet | Preload money, instant checkout, cashback support |
| ⭐ Reviews & Ratings | Rate and review movies after watching |
| 📧 Email Confirmations | Auto-send booking confirmation with all details |
| 📋 Booking History | Track current, past, and upcoming bookings |

### 🏟️ Theatre Owner Features
| Feature | Description |
|---|---|
| 🎞️ Movie Management | Add, edit, delete movie listings and shows |
| 🕐 Show Scheduling | Flexible scheduling with dynamic pricing |
| 📊 Analytics Dashboard | Revenue, occupancy, and customer insights |
| 💼 Wallet Management | Auto-receive payments when customers book |
| 🖥️ Screen Configuration | Manage multiple screens and seat layouts |

### 🛡️ Admin Features
| Feature | Description |
|---|---|
| 👥 User Management | Full CRUD on all customers and theatre owners |
| ✅ Theatre Approval | Verify and activate/deactivate theatres |
| 🔍 Booking Oversight | Monitor all bookings system-wide |
| 🗂️ Content Moderation | Approve movies and review user content |
| 📈 System Analytics | Platform-wide reporting and metrics |

---

## 🛠️ Tech Stack

<div align="center">

### Backend
![Java](https://img.shields.io/badge/Java_17-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot_2.7-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
![Spring JPA](https://img.shields.io/badge/Spring_Data_JPA-6DB33F?style=flat-square&logo=spring&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat-square&logo=apachemaven&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)

### Frontend
![React](https://img.shields.io/badge/React_18-61DAFB?style=flat-square&logo=react&logoColor=black)
![Redux](https://img.shields.io/badge/Redux_Toolkit-764ABC?style=flat-square&logo=redux&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript_ES6+-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![Axios](https://img.shields.io/badge/Axios-5A29E4?style=flat-square&logo=axios&logoColor=white)

### Database & DevOps
![MySQL](https://img.shields.io/badge/MySQL_8.0-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![IntelliJ](https://img.shields.io/badge/IntelliJ_IDEA-000000?style=flat-square&logo=intellijidea&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)

### External APIs & Services
![Razorpay](https://img.shields.io/badge/Razorpay-02042B?style=flat-square&logo=razorpay&logoColor=white)
![Google Maps](https://img.shields.io/badge/Google_Maps_API-4285F4?style=flat-square&logo=googlemaps&logoColor=white)
![Gmail SMTP](https://img.shields.io/badge/Gmail_SMTP-EA4335?style=flat-square&logo=gmail&logoColor=white)
![WebSocket](https://img.shields.io/badge/WebSocket-010101?style=flat-square&logo=socketdotio&logoColor=white)

</div>

---

## ⚙️ Installation & Setup

<div align="center">
<img src="https://user-images.githubusercontent.com/74038190/212257472-08e52665-c503-4bd9-aa20-f5a4dae769b5.gif" width="100"/>
</div>

### Prerequisites

- ☕ Java 17+
- 🟢 Node.js 18+
- 🗄️ MySQL 8.0
- 📦 Maven 3.8+

---

### 🔧 Backend Setup

```bash
# 1. Clone the repository
git clone https://github.com/SunilRavi7/Movie-Magic---Online-Ticket-Booking-System.git
cd Movie-Magic---Online-Ticket-Booking-System

# 2. Navigate to backend directory
cd backend

# 3. Create the MySQL database
mysql -u root -p
CREATE DATABASE moviemagic;
EXIT;

# 4. Configure environment variables in application.yml
# (See configuration section below)

# 5. Build and run
mvn clean install
mvn spring-boot:run
```

**`application.yml` configuration:**

```yaml
spring:
  datasource:
    url: jdbc:mysql://localhost:3306/moviemagic
    username: YOUR_DB_USERNAME
    password: YOUR_DB_PASSWORD

razorpay:
  key:
    id: YOUR_RAZORPAY_KEY_ID
    secret: YOUR_RAZORPAY_KEY_SECRET

google:
  maps:
    api:
      key: YOUR_GOOGLE_MAPS_API_KEY

spring:
  mail:
    username: YOUR_EMAIL
    password: YOUR_APP_PASSWORD

jwt:
  secret: YOUR_JWT_SECRET_KEY
```

---

### 🎨 Frontend Setup

```bash
# 1. Navigate to frontend directory
cd frontend

# 2. Install dependencies
npm install

# 3. Create .env file
echo "REACT_APP_RAZORPAY_KEY=your_razorpay_key" > .env
echo "REACT_APP_GOOGLE_MAPS_KEY=your_maps_key" >> .env

# 4. Start development server
npm start
```

The app will be running at `http://localhost:3000` with the backend at `http://localhost:8080`

---

## 🔌 API Endpoints

<details>
<summary><b>🔐 Authentication</b></summary>

| Method | Endpoint | Description |
|--------|----------|-------------|
| `POST` | `/api/v1/auth/login` | User login — returns JWT token |
| `POST` | `/api/v1/auth/register` | Register new user |

</details>

<details>
<summary><b>🎬 Movies</b></summary>

| Method | Endpoint | Description | Access |
|--------|----------|-------------|--------|
| `GET` | `/api/v1/movies` | Get all movies | Public |
| `GET` | `/api/v1/movies/search?query=` | Search movies | Public |
| `POST` | `/api/v1/movies` | Add new movie | Theatre Owner / Admin |
| `PUT` | `/api/v1/movies/{id}` | Update movie | Theatre Owner / Admin |
| `DELETE` | `/api/v1/movies/{id}` | Delete movie | Admin |

</details>

<details>
<summary><b>🎟️ Bookings</b></summary>

| Method | Endpoint | Description | Access |
|--------|----------|-------------|--------|
| `POST` | `/api/v1/bookings` | Create new booking | Customer |
| `GET` | `/api/v1/bookings/user/{userId}` | Get user's bookings | Customer |
| `GET` | `/api/v1/bookings` | Get all bookings | Admin |

</details>

<details>
<summary><b>💳 Payments</b></summary>

| Method | Endpoint | Description | Access |
|--------|----------|-------------|--------|
| `POST` | `/api/v1/payments/razorpay/callback` | Handle payment callback | System |
| `POST` | `/api/v1/payments/wallet/topup` | Add money to wallet | Customer |
| `PUT` | `/api/v1/users/wallet` | Update wallet balance | Customer |

</details>

<details>
<summary><b>🏟️ Theatres</b></summary>

| Method | Endpoint | Description | Access |
|--------|----------|-------------|--------|
| `GET` | `/api/v1/theaters/nearby` | Find nearby theatres | Public |
| `POST` | `/api/v1/theaters` | Register theatre | Theatre Owner |
| `PUT` | `/api/v1/theaters/{id}` | Update theatre info | Theatre Owner |

</details>

---

## 👥 User Roles

```
🎬 MOVIE MAGIC — 3 ROLES
│
├── 👤 CUSTOMER
│   ├── Browse & search movies
│   ├── Select seats (real-time)
│   ├── Pay via Razorpay or Wallet
│   ├── View booking history
│   └── Write reviews & ratings
│
├── 🏟️ THEATRE OWNER
│   ├── Manage theatre profile
│   ├── Add/edit movies & shows
│   ├── Configure screens & seats
│   ├── View revenue analytics
│   └── Receive payments via wallet
│
└── 🛡️ ADMIN
    ├── Approve / deactivate theatres
    ├── Manage all users
    ├── Oversee all bookings
    ├── Moderate content
    └── Full system control
```

---

## 📁 Project Structure

```
Movie-Magic---Online-Ticket-Booking-System/
│
├── 📂 backend/
│   ├── src/main/java/com/moviemagic/
│   │   ├── 📂 controller/       # REST Controllers
│   │   │   ├── MovieController.java
│   │   │   ├── BookingController.java
│   │   │   ├── PaymentController.java
│   │   │   ├── TheatreController.java
│   │   │   ├── UserController.java
│   │   │   └── AdminController.java
│   │   ├── 📂 service/          # Business Logic
│   │   │   ├── MovieService.java
│   │   │   ├── BookingService.java
│   │   │   ├── PaymentService.java
│   │   │   ├── TheatreService.java
│   │   │   ├── UserService.java
│   │   │   └── NotificationService.java
│   │   ├── 📂 entity/           # JPA Entities
│   │   │   ├── User.java
│   │   │   ├── Movie.java
│   │   │   ├── Theatre.java
│   │   │   ├── Show.java
│   │   │   ├── Booking.java
│   │   │   └── Wallet.java
│   │   ├── 📂 repository/       # Spring Data JPA Repos
│   │   ├── 📂 security/         # JWT + Spring Security
│   │   └── 📂 config/           # App & DB Config
│   ├── pom.xml
│   └── application.yml
│
├── 📂 frontend/
│   ├── src/
│   │   ├── 📂 components/       # React Components
│   │   │   ├── SeatSelection/
│   │   │   ├── BookingComponent/
│   │   │   ├── PaymentComponent/
│   │   │   └── MapComponent/
│   │   ├── 📂 pages/            # Route Pages
│   │   ├── 📂 redux/            # State Management
│   │   │   ├── authSlice.js
│   │   │   ├── moviesSlice.js
│   │   │   └── bookingsSlice.js
│   │   ├── 📂 services/         # Axios API Calls
│   │   └── App.js
│   ├── package.json
│   └── .env.example
│
├── 📂 screenshots/              # 📸 Add your screenshots here
│   ├── homepage.png
│   ├── theatre-dashboard.png
│   ├── razorpay.png
│   ├── google-maps.png
│   └── seat-selection.png
│
└── README.md
```

---

## 🎓 Internship Context

This project was developed as part of the **Internship (21INT82)** at **Zidio Development, Bengaluru** under the guidance of:

| Role | Name | Organization |
|------|------|--------------|
| Internal Guide | Dr. Bhanushree K J | Dept. of CSE, BIT |
| External Guide | Samriddhi Kumar | Zidio Development |
| Institution | Bangalore Institute of Technology | VTU, Belagavi |

**Academic Year:** 2024–25 | **USN:** 1BI22CS414

---

## 🤝 Contributing

Contributions, issues and feature requests are welcome! 

```bash
# Fork the repo → Create your branch → Commit changes → Push → Open a PR

git checkout -b feature/AmazingFeature
git commit -m 'Add some AmazingFeature'
git push origin feature/AmazingFeature
```

---

## 📬 Contact

<div align="center">

<img src="https://user-images.githubusercontent.com/74038190/214644145-264f4759-7633-441e-9d67-d8dda9d50d26.gif" width="200"/>

### **Sunil R**
*Full Stack Developer | AI & ML Enthusiast*

[![Email](https://img.shields.io/badge/Email-sunilr31r@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sunilr31r@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-SunilRavi7-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/SunilRavi7)

</div>

---

<div align="center">

![Footer](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=120&section=footer)

<br/>

**⭐ If this project helped you or impressed you, please give it a star! It motivates a lot. ⭐**

*Made with ❤️ by Sunil R | Bangalore Institute of Technology | 2024–25*

</div>
