# Week 4 - Advanced Threat Detection & Web Security Enhancements

## Project Overview
This project focuses on improving the security of a Node.js Express server through real-time intrusion detection, API hardening, and web security enhancements.

## Implemented Features

### 1. Intrusion Detection & Monitoring
- **Fail2Ban** configured separately on the server for banning IPs with multiple failed login attempts.

### 2. API Security Hardening
- **Rate Limiting** using `express-rate-limit` to prevent brute-force and DDoS attacks.
- **CORS** configured to allow only trusted origins.
- **API Key Authentication** to restrict API access to authorized users only.

### 3. Security Headers & CSP Implementation
- **Helmet.js** used to set secure HTTP headers.
- **Content Security Policy (CSP)** restricts resources to trusted domains only.
- **Strict-Transport-Security (HSTS)** forces HTTPS communication for enhanced security.

## Technologies Used
- Node.js
- Express.js
- express-rate-limit
- cors
- helmet

## How to Run

1. Install dependencies:
   ```bash
   npm install express express-rate-limit cors helmet
2. Start the server:
   node server.js
3. The server will run on http://localhost:3000.
