# Digital Studio

Digital Studio is a modern, responsive website built with Astro framework. This project showcases a professional digital studio website with clean design and optimized performance.

## 🌟 About Digital Studio

Digital Studio is a professional website that demonstrates modern web development practices using Astro, TailwindCSS, and Firebase Hosting. The site features a responsive design optimized for performance and user experience.

## 🛠️ Technologies Used

-   **Astro**: The core framework for building fast, content-focused websites.
-   **TailwindCSS**: A utility-first CSS framework for rapid UI development.
-   **Firebase Hosting**: For hosting and deployment.
-   **GitHub Actions**: For CI/CD automation.

## 🚀 Installation and Deployment

To get started with Digital Studio, follow these steps:

1. **Clone the repository**:

    ```sh
    git clone https://github.com/nagi0705/digital-studio.git
    ```

2. **Install Dependencies**:

    ```sh
    npm install
    ```

3. **Run Development Server**:

    ```sh
    npm run dev
    ```

4. **Build for Production**:

    ```sh
    npm run build
    ```

5. **Deploy to Firebase Hosting**:

    ```sh
    npx firebase-tools deploy --only hosting
    ```

## 🔄 CI/CD Pipeline

This project includes an automated CI/CD pipeline using GitHub Actions:

- **Automatic Deployment**: Pushes to the `main` branch automatically trigger deployment to Firebase Hosting
- **Build Process**: The pipeline builds the Astro project and deploys the optimized static files
- **Status Monitoring**: Check deployment status in the GitHub Actions tab

### Live Site
🌐 **Production URL**: https://digital-studio-c5abe.web.app

## 📂 Project Structure

```text
/
├── .github/
│   └── workflows/
│       └── deploy.yml          # GitHub Actions CI/CD pipeline
├── public/                     # Static assets
├── src/
│   ├── assets/                 # Images and icons
│   ├── components/             # Astro components
│   ├── layouts/
│   │   └── Layout.astro        # Main layout component
│   ├── pages/
│   │   ├── index.astro         # Home page
│   │   ├── 404.astro           # 404 error page
│   │   └── privacy-policy.mdx  # Privacy policy page
│   └── styles/
│       └── tailwind.css        # TailwindCSS styles
├── firebase.json               # Firebase configuration
├── .firebaserc                 # Firebase project settings
└── package.json                # Dependencies and scripts
```

## 🧩 Key Components

-   **Header**: Navigation and branding
-   **Hero**: Main landing section
-   **Footer**: Site footer with links
-   **Container**: Layout wrapper component
-   **Button**: Reusable button component
-   **Card**: Content card component

## 🔧 Development

### Local Development
```sh
npm run dev
```

### Build
```sh
npm run build
```

### Preview Production Build
```sh
npm run preview
```

## 📝 License

This project is licensed under the MIT License.
