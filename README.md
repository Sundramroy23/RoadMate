# RoadMate

RoadMate is a full-stack ride-hailing platform inspired by Uber, built with React (frontend) and Node.js/Express (backend). It allows users to book rides, captains to accept and complete rides, and features real-time location tracking and socket-based communication.

## Features

- **User Registration & Login:** Secure authentication for users and captains.
- **Captain Registration & Login:** Captains can register vehicles and manage rides.
- **Ride Booking:** Users can search for locations, get fare estimates, and book rides.
- **Real-Time Tracking:** Live location tracking using Google Maps API.
- **Socket Communication:** Real-time ride status updates between users and captains.
- **OTP Verification:** Secure ride start with OTP confirmation.
- **Logout & Token Blacklisting:** Secure logout for both users and captains.

## Tech Stack

- **Frontend:** React, Vite, Tailwind CSS, GSAP, @react-google-maps/api, Socket.IO Client
- **Backend:** Node.js, Express, MongoDB (Mongoose), Socket.IO, JWT, Google Maps API
- **Styling:** Tailwind CSS
- **Linting:** ESLint

## Getting Started

### Prerequisites

- Node.js & npm
- MongoDB instance
- Google Maps API Key



## Usage

- Open [http://localhost:5173](http://localhost:5173) in your browser.
- Register as a user or captain.
- Book rides, accept rides, and track ride status in real time.

## Folder Structure

```
Backend/
  controllers/
  db/
  middlewares/
  models/
  routes/
  services/
  app.js
  server.js
  socket.js
frontend/
  src/
    components/
    context/
    pages/
    App.jsx
    main.jsx
  public/
  index.html
  tailwind.config.js
  vite.config.js
```

## API Documentation

See [Backend/README.md](Backend/README.md) for detailed API endpoints and usage.

## License

MIT

---
