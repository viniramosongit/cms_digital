# 📝 CMS Digital - Lightweight Headless CMS with Intelligent SEO

Welcome to **CMS Digital**, a lightweight and efficient headless CMS designed for creating and managing posts with a strong focus on search engine optimization (SEO) and AI-powered content analysis.

## 🚀 Technologies Used

- **[Next.js](https://nextjs.org/)** – React framework for SSR and SSG
- **[Shadcdn UI](https://ui.shadcn.com/)** – UI component library
- **[Firebase](https://firebase.google.com/)** – Serverless backend for authentication and database
- **[Google Gemini API](https://ai.google.dev/)** – AI for SEO analysis and keyword suggestions
- **[Google Analytics](https://analytics.google.com/analytics/web/)** – Traffic monitoring and analysis
- **[GitHub Actions](https://github.com/features/actions)** – Automated continuous deployment
- **[Docker](https://www.docker.com/)** – Containerized development environment

## ✨ Key Features

- 📑 **Post Editing Screen** – Intuitive interface for content creation and editing
- 📊 **Google Analytics Integration** – Monitor post performance
- 🤖 **AI-Powered SEO Analysis** – Automated SEO evaluation for each post
- 🔑 **AI-Driven Keyword Suggestions** – Recommendations for better search optimization
- 🔐 **Firebase Authentication** – Secure and scalable user management
- 🐳 **Firebase Emulator with Docker** – Local development environment for Firebase services

## 🏗️ Project Structure

```plaintext
📂 cms-digital
├── 📁 firebase        # Files for run firebase emulator in docker
|   ├── 📜 firebase.json   # Firebase configuration
|   ├── 📜 Dockerfile      # File for create docker image
├── 📁 public          # Public files and assets
├── 📁 src
│   ├── 📁 components  # Reusable UI components
│   ├── 📁 pages       # CMS pages
│   ├── 📁 services    # Firebase and Gemini API integrations
│   ├── 📁 styles      # Global and theme styles
│   ├── 📁 utils       # Utility functions
├── 📜 next.config.js  # Next.js configuration
├── 📜 docker-compose.yml  # Docker configuration for Firebase emulator
├── 📜 .github/workflows/deploy.yml  # CI/CD with GitHub Actions
└── 📜 README.md       # Project documentation
```

## 🛠️ How to Run the Project

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/cms-digital.git
   cd cms-digital
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Create required accounts and generate API tokens:
   - **[Firebase](https://firebase.google.com/)**: Create a Firebase project and generate an API key.
   - **[Google Gemini API](https://ai.google.dev/)**: Sign up for Google Gemini API and obtain an API key.
   - **[Google Analytics](https://analytics.google.com/analytics/web/)**: Set up Google Analytics and retrieve the tracking ID.

4. Configure environment variables (`.env.local`):
   ```sh
   NEXT_PUBLIC_FIREBASE_API_KEY=your_firebase_api_key
   NEXT_PUBLIC_GEMINI_API_KEY=your_gemini_api_key
   NEXT_PUBLIC_ANALYTICS_ID=your_google_analytics_id
   ```

### 🐳 Running Firebase Emulator with Docker

For local development, Firebase services are containerized with Docker. To start the emulator, follow these steps:

1. Ensure **Docker** is installed and running on your machine.
2. Run the following command to start the Firebase emulator:
   ```sh
   docker-compose up -d
   ```
3. To stop the emulator:
   ```sh
   docker-compose down
   ```
4. The Firebase Emulator UI will be accessible at `http://localhost:4000`.

5. Start the development server:
   ```sh
   npm run dev
   ```

## 🚀 Deployment

This project uses **GitHub Actions** for automated continuous deployment. Every push to the `main` branch triggers a new build and deployment automatically.

## 📌 Best Practices Applied

✅ **SEO-Friendly** – Optimized for efficient search engine indexing<br>
✅ **Componentization** – Reusable code for maintainability<br>
✅ **Security** – Authentication and permission management via Firebase<br>
✅ **Performance** – Utilizes Server-Side Rendering (SSR) and Static Site Generation (SSG) in Next.js<br>
✅ **CI/CD** – Automated deployment to prevent manual errors<br>
✅ **Containerization** – Local Firebase development with Docker

## 📞 Contact

If you enjoyed this project and want to know more, feel free to reach out:

🔗 [LinkedIn](https://www.linkedin.com/in/viniramos)
🔗 [X](https://www.x.com/viniramosonx)
🔗 [Website](https://www.vinidigital.com.br)



