# OTP Generator

A simple React application that generates a random 6-digit One-Time Password (OTP) and automatically expires it after 5 seconds.

## Features

* Generate random 6-digit OTPs
* 5-second countdown timer
* Automatic OTP expiration
* Button disabled while OTP is active
* Generate a new OTP after expiration
* Built using React Hooks

## Technologies Used

* React
* Vite
* JavaScript (ES6+)
* CSS

## Getting Started

### Clone the repository

```bash
git clone https://github.com/your-username/otp-generator.git
```

### Navigate to the project

```bash
cd otp-generator
```

### Install dependencies

```bash
npm install
```

### Run the development server

```bash
npm run dev
```

Open the local URL shown in the terminal to view the application.

## Project Structure

```text
src/
├── App.jsx
├── App.css
├── index.css
├── main.jsx
└── otp-generator.jsx
```

## How It Works

1. Click the **Generate OTP** button.
2. A random 6-digit OTP is generated.
3. A 5-second countdown begins.
4. The button is disabled during the countdown.
5. When the timer reaches zero, the OTP expires.
6. The button becomes available again to generate a new OTP.

## Learning Concepts

This project demonstrates:

* React Components
* useState Hook
* useEffect Hook
* useRef Hook
* Event Handling
* Conditional Rendering
* Timer Management with setInterval and clearInterval

## Author

Ayush

## License

This project is for educational purposes.
