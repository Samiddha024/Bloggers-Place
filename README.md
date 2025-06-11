# 📝 React + Appwrite Blog App

A minimal full-stack blog application built using **React** and **Appwrite**.

## 🚀 Features

- ✨ User Signup & Login
- 🔐 Authentication via Appwrite
- 📝 Create and Post Blogs (Rich Text Editor)
- 📃 View All Blog Posts
- 🚪 Logout functionality

## ⚙️ Tech Stack

- **Frontend**: React, Tailwind CSS, React Hook Form, Redux Toolkit
- **Backend (BaaS)**: Appwrite
- **Editor**: TinyMCE (`@tinymce/tinymce-react`)

## 📁 Project Structure

```

src/
├── appwrite/           # Appwrite SDK and config
│   └── auth.js
├── components/         # Reusable components
│   ├── Header.jsx
│   ├── Button.jsx
│   ├── RTE.jsx
│   └── ...
├── pages/              # Page-level components
├── store/              # Redux state management
├── App.jsx             # Root component
└── main.jsx            # Entry point

````

## 🔑 Environment Variables

Create a `.env` file and add:

```env
VITE_APPWRITE_URL=your_appwrite_endpoint
VITE_APPWRITE_PROJECT_ID=your_project_id
VITE_APPWRITE_DATABASE_ID=your_database_id
VITE_APPWRITE_COLLECTION_ID=your_collection_id
VITE_APPWRITE_BUCKET_ID=your_bucket_id
````

> Replace the values with those from your Appwrite console.

## 🛠️ Installation

```bash
# Clone the repository
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

# Install dependencies
npm install

# Start the development server
npm run dev
```
