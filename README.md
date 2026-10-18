# 📁 Storage and File Sharing Platform

A modern, responsive web application for uploading, managing, organizing, and sharing files securely. This personal project was built using **Next.js, React, TypeScript, Tailwind CSS, and Appwrite**, with a focus on user authentication, efficient file management, and a clean user experience.

## 🚀 Overview

The Storage and File Sharing Platform provides users with a centralized space to store and manage their files. It supports multiple file formats, allowing users to upload, preview, download, rename, delete, and share files through an intuitive interface.

The application also features a dashboard that provides an overview of storage usage, recent uploads, and file categories.

## 🛠️ Tech Stack

* **Frontend:** React 19, Next.js 15
* **Programming Language:** TypeScript
* **Styling:** Tailwind CSS
* **UI Components:** ShadCN UI
* **Backend & Database Services:** Appwrite
* **File Storage:** Appwrite Storage
* **Authentication:** Appwrite Authentication

## ✨ Key Features

* **User Authentication:** Sign up, log in, and log out using Appwrite Authentication.
* **File Uploads:** Upload documents, images, videos, audio files, and other supported file types.
* **File Management:** View, preview, rename, and delete uploaded files.
* **File Downloads:** Download stored files whenever needed.
* **File Sharing:** Share files with other users for easier access and collaboration.
* **Storage Dashboard:** Monitor storage usage, recent uploads, and file distribution by category.
* **Global Search:** Quickly search for files and shared content.
* **File Sorting:** Organize files by name, creation date, or file size.
* **Responsive UI:** Access the application through a clean, modern interface designed for different screen sizes.

## 📂 File Categories

The platform organizes files into the following categories:

* 📄 Documents
* 🖼️ Images
* 🎬 Media
* 📦 Other Files

## ⚙️ Getting Started

Follow these steps to run the project locally.

### Prerequisites

Make sure you have the following installed:

* Node.js
* npm
* Git

### 1. Clone the Repository

```bash
git clone <your-github-repository-url>
cd <your-project-folder>
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Configure Environment Variables

Create a `.env.local` file in the root directory and add your Appwrite configuration:

```env
NEXT_PUBLIC_APPWRITE_ENDPOINT="https://cloud.appwrite.io/v1"
NEXT_PUBLIC_APPWRITE_PROJECT=""
NEXT_PUBLIC_APPWRITE_DATABASE=""
NEXT_PUBLIC_APPWRITE_USERS_COLLECTION=""
NEXT_PUBLIC_APPWRITE_FILES_COLLECTION=""
NEXT_PUBLIC_APPWRITE_BUCKET=""
NEXT_APPWRITE_KEY=""
```

Replace the empty values with the appropriate configuration from your Appwrite project.

**Security Note:** Never commit secret API keys or sensitive credentials to a public repository. Keep server-side secrets private and ensure that client-side environment variables contain only values intended to be publicly accessible.

### 4. Start the Development Server

```bash
npm run dev
```

Open `http://localhost:3000` in your browser to access the application.

## 🎯 Project Goals

This project explores modern web development practices, including:

* Building responsive interfaces with React and Next.js.
* Implementing authentication and backend services using Appwrite.
* Managing file uploads and storage operations.
* Creating reusable UI components with TypeScript and Tailwind CSS.
* Organizing files through search, filtering, and sorting functionality.
* Designing an intuitive dashboard for monitoring storage usage.

## 🔮 Future Improvements

Potential enhancements for future versions include:

* Advanced file-sharing permissions.
* Improved file search and filtering.
* File version history.
* Enhanced security and access controls.
* Additional storage analytics.
* Support for bulk file operations.

## 👨‍💻 About

This repository contains my personal project exploring full-stack web development, cloud-based file storage, authentication, and modern UI development.

I built this project to strengthen my understanding of the Next.js ecosystem and learn how frontend applications integrate with backend services and cloud storage.

---

⭐ If you find this project useful, consider giving the repository a star!
