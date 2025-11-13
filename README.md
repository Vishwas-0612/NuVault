# NuVault – Modern Cloud Storage Platform

![NuVault Banner](https://img.shields.io/badge/NuVault-Cloud%20Storage-blueviolet?style=for-the-badge)
![Next.js](https://img.shields.io/badge/Next.js-14-black?style=for-the-badge&logo=nextdotjs)
![Appwrite](https://img.shields.io/badge/Appwrite-Cloud-f02e65?style=for-the-badge&logo=appwrite)
![TypeScript](https://img.shields.io/badge/TypeScript-5-blue?style=for-the-badge&logo=typescript)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

NuVault is a secure, fast, and intuitive cloud storage platform inspired by Google Drive.
It allows users to upload, store, organize, preview, and manage files seamlessly — all inside a beautiful, minimal, and high-performance interface.

Built with **Next.js • Appwrite • TypeScript • Modern UI/UX**

---

## 🚀 Features

### 🔐 Authentication
- **Appwrite's** Email-based OTP login
- Secure session management
- Appwrite accounts & token-based flow

### 📁 File Storage
- Upload any file type
- Real-time upload progress
- Automatic metadata extraction
- Private URLs with secure access

### 🗂️ File Management
- Create folders
- Drag & drop uploads
- Rename, delete, move files
- Image, PDF & text preview

### 🔗 Sharing
- Public shareable links
- Link expiration support
- Toggle public/private access

### ⚡ UI/UX
- Modern, responsive dashboard
- Smooth animations
- Productivity-focused minimal UI

### 🛡 Security
- Users can access only their own files
- Fully protected Appwrite buckets
- Backend APIs secured with API keys
- Robust data validation and sanitization for API inputs (Added for best practices)

---

## 🧰 Tech Stack

| **Layer**      | **Technology**                                         |
| -------------- | ------------------------------------------------------ |
| **Frontend**   | Next.js 14 (App Router), React, TypeScript             |
| **Backend**    | Appwrite Cloud (Authentication, Storage, Database)     |
| **UI**         | TailwindCSS + ShadCN                                   |
| **Storage**    | Appwrite Buckets with Permissions                      |
| **Deployment** | Appwrite Cloud                                         |

---

## 📦 Project Structure

📦 NuVault/
┣ 📁 app/
│ ┣ 📁 auth/
│ ┣ 📁 dashboard/
│ ┗ 📁 upload/
┣ 📁 components/
┣ 📁 lib/
┣ 📁 styles/
┣ 📁 utils/
┗ 📄 README.md


---

## 📦 Getting Started

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/vishwas-0612/NuVault.git
cd NuVault
```

### 2️⃣ Install Dependencies

```bash
npm install
```

### 3️⃣ Create a .env.local File

```bash
NEXT_PUBLIC_APPWRITE_ENDPOINT=&lt;your-appwrite-endpoint&gt;
NEXT_PUBLIC_APPWRITE_PROJECT_ID=&lt;your-project-id&gt;
NEXT_PUBLIC_APPWRITE_BUCKET_ID=&lt;your-bucket-id&gt;
APPWRITE_API_KEY=&lt;your-appwrite-api-key&gt;
```

### 4️⃣ Run the Development Server

```bash
npm run dev
```

## ⭐ Like the project?
If you find this useful, consider giving the repo a star ⭐ on GitHub!
