# 📁 FileBud

**FileBud** is a backend application for **file storage and management**, inspired by Google Drive.  
It enables users to securely upload, organize, and stream their files with ease.

Built using **Node.js**, **Express**, and **MongoDB**, the project demonstrates key backend principles such as authentication, file handling, and efficient data streaming.

---

## 🚀 Demo
*(Add your deployed link or API documentation link here once available)*

---

## ✨ Features

- **User Authentication & Authorization**  
  Secure account creation and login using **JWT** and **bcrypt**.

- **File Uploads**  
  Upload files of multiple types, stored in **Cloudinary**.

- **Folder Management**  
  Create, delete, and organize files within folders.

- **File Management**  
  Search, download, delete, and preview files directly in the browser.

- **Media Streaming**  
  Stream videos using data chunking for efficient performance.

---

## 🛠️ Tech Stack

| Layer | Technology |
|:------|:------------|
| **Backend** | Node.js, Express |
| **Database** | MongoDB, Mongoose |
| **Authentication** | JWT, bcrypt |
| **File Handling** | Multer, Cloudinary |
| **Middleware** | Cookie-parser |

---

## ⚙️ Installation

### 1️⃣ Clone the repository

```
git clone https://github.com/harsh25023/File-Bud.git
cd file-bud
```

### 2️⃣ Install dependencies

```
npm install
```
### 3️⃣Set up environment variables Create a `.env` file in the root directory and add the following:

```env
PORT=your_port
CORS_ORIGIN=*
MONGODB_URI=your_mongodb_api_key

ACCESS_TOKEN_SECRET=your_access_token_secret
ACCESS_TOKEN_EXPIRY=your_access_token_expiry
REFRESH_TOKEN_SECRET=your_refresh_token_secret
REFRESH_TOKEN_EXPIRY=your_refresh_token_expiry

CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
```

### 4️⃣ Start the application

```
npm run dev
```
---

## 🧭 Usage Guide
  1. Create an Account: Sign up using the provided endpoint.
  2. Upload Files: Upload files to Cloudinary via the upload endpoint.
  3. Manage Files and Folders: Use the respective endpoints to create/delete folders, search, download, and delete files.
  4. Stream Media: View images and videos directly in the browser.

---

## Important Concepts
  1. Mongoose Transactions: Ensures consistent and reliable database operations.
  2. Retry Mechanisms: Handles failures and minimizes data loss.
  3. Efficient Data Handling: Optimized schema design for faster queries and minimal delays.
  4. Production-level Code Quality: Robust error handling and good coding practices.

---

## Acknowledgements 
  1. Inspiration from Google Drive for the application's core concept.
  2. Libraries and frameworks used: Express, MongoDB, Mongoose, JWT, bcrypt, Multer, Cloudinary, and Cookie-parser.


