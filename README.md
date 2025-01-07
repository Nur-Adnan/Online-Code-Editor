# CodeDev: The Ultimate Online Code Editor 🌐💻

Welcome to **CodeCraft**, a fully-featured browser-based coding platform designed to streamline your development workflow. Built with **Next.js 15**, **Convex**, **Clerk**, and **TypeScript**, this platform offers robust features and a seamless user experience.

---

## 🚀 Live Demo

[Live Demo](https://online-code-editor-ten-dun.vercel.app/) 

---

## 📌 Features

### Core Functionality:
- 🖥️ **Multi-language Support**: Write and execute code in 10+ languages.
- 🎨 **Customizable Themes**: Choose from 5 VSCode-inspired themes.
- ✅ **Smart Output Handling**: Real-time feedback with Success & Error states.
- 🖇️ **Webhook Integration**: Connect to external tools effortlessly.

### User Features:
- 🔐 **Clerk Integration**: Secure authentication and profile management.
- 📈 **Execution History**: Track your coding activity.
- 👨‍💻 **Community Sharing**: Share and discover code snippets.
- 🔍 **Advanced Search**: Filter code snippets and projects with ease.
- 💡 **Customizable Font Sizes**: Adjust your editor to fit your needs.

### Performance & Design:
- ⚡ **Fast and Responsive**: Optimized for speed and scalability.
- 🔍 **Search Engine Optimized (SEO)**: Enhance your project’s visibility.
- 🔬 **Modern UI/UX**: Built with Tailwind CSS for a clean and responsive design.

---

## 🛠️ Tech Stack

### Frontend:
- [Next.js 15](https://nextjs.org/) - Modern React Framework
- [TypeScript](https://www.typescriptlang.org/) - Type-safe development
- [Tailwind CSS](https://tailwindcss.com/) - Customizable UI components

### Backend:
- [Node.js](https://nodejs.org/) - Server-side environment
- [Convex](https://convex.dev/) - State management and data synchronization
- [Clerk](https://clerk.dev/) - Authentication and user management

### Tools & Integrations:
- **Webhook Support** - Real-time notifications and updates
- **Deployment** - Optimized for production environments

---

## 🖥️ Getting Started

### Prerequisites
- **Node.js**: v16 or higher
- **npm**: v7 or higher

### Installation

#### Create a `.env` file with the following:
```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your-clerk-publishable-key
CLERK_SECRET_KEY=your-clerk-secret-key
CONVEX_DEPLOYMENT=your-convex-deployment-url
NEXT_PUBLIC_CONVEX_URL=your-convex-url
```

#### Add these `.env` to Convex Dashboard
```env
CLERK_WEBHOOK_SECRET=your-clerk-webhook-secret
LEMON_SQUEEZY_WEBHOOK_SECRET=your-lemon-squeezy-webhook-secret
```

### Run the app:
```bash
npm install
npm run dev
```

### Open your browser and navigate to:
```bash
http://localhost:3000
```

---

## 📂 Project Structure
```plaintext
🗁 /convex          # State management and server logic
🗁 /public          # Static assets
🗁 /src             # Main application source code
├── /components     # Reusable React components
├── /pages          # Next.js page routes
├── /styles         # Tailwind and custom CSS styles
├── /utils          # Utility functions
```

---

## 🌈 Screenshots

- **Customizable Themes and Code Editor**:
  
  ![Online-Code-Editor---Adnan](https://github.com/user-attachments/assets/ede85468-448e-42ff-9cc4-ec64c579c3bd)

- **Dashboard with Execution History**:

  ![Online-Code-Editor](https://github.com/user-attachments/assets/6d9d2b00-88e6-40ac-ab6a-ba1236886072)
  ![2](https://github.com/user-attachments/assets/bec536c7-4995-4bb4-9c9f-40f2759d274a)

---

## 🛠️ Deployment

1. **Environment Setup**: Ensure all `.env` variables are properly configured.
2. **Production Build**:
   ```bash
   npm run build
   npm start
   ```
3. **Hosting**: Deploy on platforms like Vercel, Netlify, or AWS.

---
