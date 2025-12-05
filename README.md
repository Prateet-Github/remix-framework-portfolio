# Prateet.dev - Portfolio Website 🚀

A modern, production-ready portfolio website built with React Router (Remix framework) and deployed on Vercel.

<img width="1470" height="832" alt="Screenshot 2025-12-06 at 4 27 09 AM" src="https://github.com/user-attachments/assets/124ffcc0-3d91-4a26-b20b-e6b4ec42ab69" />


**Live Site**: [remix-framework-portfolio.vercel.app](https://remix-framework-portfolio.vercel.app)

---

## 📋 Overview

This is a personal portfolio website showcasing my work as a Full Stack Developer. Built with React Router and TypeScript, it features server-side rendering, smooth animations, and a modern design with TailwindCSS.

---

## ✨ Features

- 🎨 Modern and responsive design
- ⚡ Server-side rendering (SSR) with React Router
- 🎭 Smooth animations with Framer Motion
- 📱 Mobile-first responsive layout
- 🌙 Clean and professional UI
- 📬 Contact form integration
- 🚀 Fast page loads and optimized performance
- 🎯 SEO optimized
- 📦 Docker support for containerized deployment

---

## 🛠️ Tech Stack

| Category | Technology |
|----------|-----------|
| **Framework** | React Router v7 |
| **Language** | TypeScript |
| **Styling** | TailwindCSS |
| **Animations** | Framer Motion |
| **Build Tool** | Vite |
| **Deployment** | Vercel |
| **Containerization** | Docker |

---

## 📁 Project Structure

```
remix-framework-portfolio/
├── app/                    # Application code
│   ├── routes/            # Route components
│   ├── components/        # Reusable components
│   └── styles/            # Global styles
├── public/                # Static assets
│   └── images/           # Project screenshots
├── .dockerignore          # Docker ignore file
├── Dockerfile             # Docker configuration
├── package.json           # Dependencies
├── react-router.config.ts # React Router configuration
├── tsconfig.json          # TypeScript configuration
├── vite.config.ts         # Vite configuration
└── README.md              # Documentation
```

---

## 🚀 Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Prateet-Github/remix-framework-portfolio.git
   cd remix-framework-portfolio
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   
   Navigate to `http://localhost:5173`

---

## 📦 Available Scripts

| Script | Description |
|--------|-------------|
| `npm run dev` | Start development server with HMR |
| `npm run build` | Build for production |
| `npm run start` | Start production server |
| `npm run typecheck` | Run TypeScript type checking |

---

## 🏗️ Building for Production

Create a production build:

```bash
npm run build
```

This will generate optimized files in the `build/` directory:
```
build/
├── client/    # Static assets
└── server/    # Server-side code
```

---

## 🐳 Docker Deployment

### Build Docker Image

```bash
docker build -t remix-portfolio .
```

### Run Container

```bash
docker run -p 3000:3000 remix-portfolio
```

The application will be available at `http://localhost:3000`

### Docker Deployment Platforms

This containerized application can be deployed to:
- AWS ECS
- Google Cloud Run
- Azure Container Apps
- Digital Ocean App Platform
- Fly.io
- Railway

---

## 🌐 Deployment to Vercel

The easiest way to deploy this React Router app:

1. **Push your code to GitHub**

2. **Import to Vercel**
   - Go to [vercel.com](https://vercel.com)
   - Click "New Project"
   - Import your repository
   - Vercel will auto-detect React Router

3. **Deploy**
   - Click "Deploy"
   - Your site will be live in minutes!

---

## 📄 Portfolio Sections

### 1. Hero Section
- Introduction and call-to-action
- Professional tagline
- Quick navigation buttons

### 2. About Me
- Personal introduction
- Professional background
- Downloadable CV

### 3. Skills & Expertise
- **Frontend**: React, Next.js, Remix, TailwindCSS, Framer Motion
- **Backend**: Node.js, Express.js, Supabase, MongoDB, REST APIs
- **Programming**: JavaScript, TypeScript, C++, Python
- **Tools**: Git, VS Code, Vercel, Postman, Figma

### 4. Featured Projects
- **GetRides**: Ride hailing platform with real-time tracking
- **SmartBuy**: AI-powered device recommendation platform
- **MyMap**: Alternative to Google Maps with custom routing

### 5. Contact Section
- Contact form
- Email and phone information
- Location details
- Social media links

---

## 🎨 Customization

### Updating Content

Edit the route files in `app/routes/` to update:
- Personal information
- Project details
- Skills and expertise
- Contact information

### Styling

TailwindCSS is configured and ready to use. Modify:
- `app/styles/` for global styles
- Component files for component-specific styles

### Adding Projects

Add new project images to `public/` and update the projects section in the routes.

---

## 🔧 Configuration Files

### `react-router.config.ts`
Configuration for React Router routing and SSR settings.

### `vite.config.ts`
Vite build tool configuration for optimized bundling.

### `tsconfig.json`
TypeScript compiler options and type checking configuration.

---

## 📱 Responsive Design

The portfolio is fully responsive and optimized for:
- 📱 Mobile devices (320px+)
- 📲 Tablets (768px+)
- 💻 Laptops (1024px+)
- 🖥️ Desktops (1440px+)

---

## 🚀 Performance

- Server-side rendering for instant page loads
- Optimized asset bundling
- Lazy loading for images
- Code splitting for faster initial load
- Lighthouse score: 95+

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 👨‍💻 Author

**Prateet Tiwari**
- Portfolio: [remix-framework-portfolio.vercel.app](https://remix-framework-portfolio.vercel.app)
- GitHub: [@Prateet-Github](https://github.com/Prateet-Github)
- Email: prateettiwari29@gmail.com
- Location: Delhi, India

---

## 🙏 Acknowledgments

- [React Router](https://reactrouter.com/) for the amazing framework
- [TailwindCSS](https://tailwindcss.com/) for the utility-first CSS
- [Framer Motion](https://www.framer.com/motion/) for smooth animations
- [Vercel](https://vercel.com) for seamless deployment

---

<div align="center">
  <p>⭐ If you like this project, please give it a star on GitHub! ⭐</p>
  <p>Made with ❤️ by Prateet Tiwari</p>
  <p>© 2025 All rights reserved</p>
</di
