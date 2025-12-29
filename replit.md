# Knight Bot - WhatsApp Pair Code Generator

## Overview
A Node.js Express application that generates WhatsApp pairing codes and QR codes for linking WhatsApp devices.

## Project Structure
- `index.js` - Main Express server entry point (port 5000)
- `pair.js` - Router for pair code generation endpoint
- `qr.js` - Router for QR code generation endpoint
- `pair.html` - Frontend HTML page with toggle between pair code and QR code modes
- `mega.js` - Additional module

## Tech Stack
- Node.js 20+
- Express.js for server
- @whiskeysockets/baileys for WhatsApp integration
- qrcode for QR generation

## Running
The app runs on port 5000 and serves a web interface where users can:
1. Enter their WhatsApp number to get a pair code
2. Generate a QR code for device linking

## Development
```bash
npm install
npm start
```

## Deployment
Configured for autoscale deployment with `npm start` command.
