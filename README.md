# Artsy Tarsy - Cake Shop Website

A full-stack web application designed for a digital cake shop storefront. This project showcases the shop's services and products, providing a platform for customers to explore various cake designs and services.

## 🚀 Features

- **Service Showcase:** Display various cake services and specialized designs.
- **Dynamic Content:** Utilizes Pug for server-side rendering of dynamic views.
- **Data Persistence:** Integrated with MongoDB via Mongoose for managing shop-related data.
- **Modern Backend:** Built with Node.js and the Express.js framework.

## 🛠️ Technology Stack

- **Frontend:** Pug (Template Engine), CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Tools:** Mongoose, Body-Parser, Nodemon (for development)

## 📋 Prerequisites

- [Node.js](https://nodejs.org/) (v14+ recommended)
- [MongoDB](https://www.mongodb.com/) installed and running locally

## 🔧 Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/NidhiSingh25901/artsy-tarsy-.git
   cd artsy-tarsy-
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Database Configuration:**
   Ensure your MongoDB server is running. By default, the application connects to a local instance. You can modify the connection string in `app.js`.

## 🏃 Running the Application

To start the server in development mode (with auto-reload):
```bash
npm start
```
*Note: The project uses nodemon for easy development.*

The application will be accessible at `http://localhost:80` (or the port specified in `app.js`).

## 📁 Project Structure

- `app.js`: Main entry point and server configuration.
- `views/`: Pug templates for the application pages.
- `static/`: Static assets including CSS and images.
- `package.json`: Project metadata and dependencies.

---
*Developed by Nidhi*
