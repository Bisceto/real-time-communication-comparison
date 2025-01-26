# Real-Time Communication Protocols

## Overview

This project compares real-time communication protocols using Next.js (frontend) and Express.js (backend) in TypeScript.

## Setup

1. Install dependencies:

   ```bash
   cd frontend && npm install && cd ../backend && npm install
   ```

2. Run the backend:

   ```bash
   cd backend && npx ts-node src/server.ts
   ```

3. Run the frontend:

   ```bash
   cd frontend && npm run dev
   ```

4. Access the frontend at [http://localhost:3000](http://localhost:3000)

## Docker Setup

To run the application using Docker:

```bash
docker-compose up --build
```

## Features

- WebSockets for real-time communication
- REST API for traditional polling methods
