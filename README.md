# Doctor Appointment Platform 🥼

A comprehensive appointment scheduling solution built with MongoDB, Express, React, and Node.js.

<img src='https://github.com/user-attachments/assets/768d1f94-29e3-4466-90c5-418278abb2ce' width="100%"/>

## 💡 Project Overview

This application enables users to register, book, view, and cancel appointments with medical professionals. It has three main components:

1. **Backend API**: Handles data storage and retrieval using MongoDB and Express.
2. **Patient Frontend**: A React-based interface where users can sign up/in, browse doctors by specialty, view profiles, and select available slots.
3. **Admin Dashboard**: Allows administrators to manage doctor profiles, including adding or editing educational details, specializations, and photos.

The development took three weeks and provided valuable hands-on experience with the MERN stack and Tailwind CSS.

## ⚡ Technologies Used

- **MongoDB**
- **Express.js**
- **React**
- **Node.js**
- **Tailwind CSS**
- **JWT Auth**

## 🛠 Key Dependencies

- `axios`
- `react-router-dom`
- `react-toastify`

## 🚦 Local Setup Instructions

To run this project locally, follow the steps below.

### 1️⃣ Prerequisites

- [Vite](https://vitejs.dev/) installed globally
- Node.js (v14 or later)
- A MongoDB cluster (free tier or higher)

### 2️⃣ Configure Environment Variables

Create a `.env` file in the project root and add your MongoDB connection string:

```bash
MONGODB_URI=mongodb+srv://<username>:<password>@clusterName.xxxxxxx.mongodb.net/doctor-appointment
```

```bash
VITE_BACKEND_URL = http://localhost:4000
```

```bash
JWT_SECRET = yourkey
```

### 3️⃣ Backend Setup

1. Navigate to the root folder:
   ```bash
   cd doctor-appointment-website
   ```
2. Install server dependencies:
   ```bash
   npm install
   ```
3. Start the backend server:
   ```bash
   npm run server
   ```
4. Open the API in your browser at [http://localhost:4000](http://localhost:4000).

### 4️⃣ Frontend (Patient Portal)

1. Switch to the frontend directory:
   ```bash
   cd doctor-appointment-website/frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Launch the development server:
   ```bash
   npm run dev
   ```
4. View the patient interface at [http://localhost:5173](http://localhost:5173).

### 5️⃣ Admin Dashboard

1. Change into the admin folder:
   ```bash
   cd doctor-appointment-website/admin
   ```
2. Install admin dependencies:
   ```bash
   npm install
   ```
3. Run the admin server:
   ```bash
   npm run dev
   ```
4. Access the admin panel at [http://localhost:5174](http://localhost:5174).

### 6️⃣ Since this is a dynamic website, you need to insert relevant data into your MongoDB database to display

## 🌍 Demo Preview

<details>
  <summary>📸 Click to expand screenshots</summary>

  <img src='https://github.com/user-attachments/assets/768d1f94-29e3-4466-90c5-418278abb2ce' style="width:100%; margin-bottom: 20px; border-bottom: 5px solid black;" />

  <img src='https://github.com/user-attachments/assets/c66e8a38-6c8f-4b07-ab43-4ede3c087a09' style="width:100%; margin-bottom: 20px; border-bottom: 5px solid black;" />

  <img src='https://github.com/user-attachments/assets/6bc93c7b-2e47-414a-ac9c-f7abbe8871b4' style="width:100%; margin-bottom: 20px; border-bottom: 5px solid black;" />

  <img src='https://github.com/user-attachments/assets/ba5625b0-2a40-4429-b3c8-e6a5f4e23676' style="width:100%; margin-bottom: 20px; border-bottom: 5px solid black;" />

  <img src='https://github.com/user-attachments/assets/7d6f1afb-f767-4464-8189-33df6a1cc2b8' style="width:100%; margin-bottom: 20px; border-bottom: 5px solid black;" />

  <img src='https://github.com/user-attachments/assets/c7d8da6e-6bc4-485a-a6ce-8ed52ceff819' style="width:100%; margin-bottom: 20px; border-bottom: 5px solid black;" />

  <img src='https://github.com/user-attachments/assets/b062d12a-46ab-4b68-a6fa-89d0dc455699' style="width:100%; margin-bottom: 20px; border-bottom: 5px solid black;" />

</details>
