# Payag-ni-Gaston
This project is a sophisticated, single-file Client Booking Web Application designed for the "Payag ni Gaston" resort or cottage rental. It serves as both a public-facing pricing display and a dynamic reservation tool, notably featuring a workflow for handling custom, negotiated pricing.

** Folder Structure (Recommended) **
```
payag-ni-gaston/
│
├── public/
│   ├── index.html
│   ├── favicon.ico
│   └── logo.png
│
├── src/
│   ├── assets/
│   │   ├── images/
│   │   │   ├── beach.jpg
│   │   │   ├── cottages/
│   │   │   └── kayak.jpg
│   │   └── icons/
│   │
│   ├── components/
│   │   ├── Navbar.tsx
│   │   ├── Footer.tsx
│   │   ├── HeroSection.tsx
│   │   ├── BookingForm.tsx
│   │   └── PlanCard.tsx
│   │
│   ├── pages/
│   │   ├── Home.tsx
│   │   ├── Pricing.tsx
│   │   ├── Booking.tsx        <-- 📌 turn this into modal not a page
│   │   ├── Login.tsx          <-- 📌 turn this into modal in Home Page not a page
│   │   ├── Signup.tsx         <-- 📌 turn this into modal in Home Page not a page
│   │   └── AdminDashboard.tsx
│   │
│   ├── routes/
│   │   ├── AppRouter.tsx      <-- handles React Router paths
│   │
│   ├── services/
│   │   ├── firebase.ts        <-- Firebase config and exports
│   │   ├── authService.ts     <-- Authentication helper (login/signup)
│   │   └── bookingService.ts  <-- Firestore or RTDB CRUD functions
│   │
│   ├── styles/
│   │   ├── global.css
│   │   ├── navbar.css
│   │   ├── pricing.css
│   │   └── footer.css
│   │
│   ├── App.tsx
│   ├── main.tsx
│   └── vite-env.d.ts
│
├── firebase.json
├── package.json
├── tsconfig.json
└── README.md
```