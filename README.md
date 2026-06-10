# Vercl.com - AI-Powered Digital Creator Studio 🚀

Vercl.com is an AI-powered digital creator studio designed for automation, content generation, and modern web deployment using Vercel. It functions as a Vercel-ready AI automation studio, featuring content generation tools, modular UI components, and a scalable frontend architecture for rapid SaaS deployment. This platform aims to be an all-in-one solution for creators to build, automate, and manage their digital presence.

[![Vercel Deploy](https://img.shields.io/badge/Deploy%20on%20Vercel-black?style=for-the-badge&logo=vercel)](https://vercel.com/new/git/external?repository-url=https://github.com/rananisarsb51214-web/Vercl.com)

## ✨ Features

- **AI-Powered Content Generation**: Leverages AI to assist in creating and enhancing content.
- **Modular UI Components**: Built with reusable components for a flexible user interface.
- **Scalable Frontend Architecture**: Designed for rapid SaaS deployment using Next.js and Vercel.
- **Link Management**: A dashboard for managing and organizing various links.
- **Post Creation Studio**: An integrated tool for designing social media posts with AI assistance.
- **Theme Customization**: Options to customize themes, fonts, and colors for content creation.
- **Dark Mode Support**: Responsive design with a dark mode option.
- **Progressive Web App (PWA)**: Potential for installable web application capabilities.

## 🛠️ Tech Stack

- **Frontend**: React, Next.js, TypeScript, Vite, Tailwind CSS
- **Backend/AI**: Node.js, Google Generative AI (Gemini)
- **Deployment**: Vercel
- **Development Tools**: VS Code

## 🚀 Installation

**Prerequisites:**

- Node.js installed on your system.
- npm or yarn package manager.

**Steps:**

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/rananisarsb51214-web/Vercl.com.git
    cd Vercl.com
    ```

2.  **Install dependencies:**
    ```bash
    npm install
    # or
    yarn install
    ```

3.  **Set up environment variables:**
    Create a `.env.local` file in the root directory and add your Gemini API key:
    ```env
    GEMINI_API_KEY=YOUR_GEMINI_API_KEY
    ```

4.  **Run the development server:**
    ```bash
    npm run dev
    # or
    yarn dev
    ```
    The application will be accessible at `http://localhost:3000` (or the port specified in `vite.config.ts`).

## 💡 Usage

Vercl.com provides a creative suite for digital creators:

1.  **Home Page**: Explore the main landing page featuring a hero section, portfolio link, and a call to action to open the studio or manage links. It also showcases responsive social media templates.
2.  **Post Creator Studio (`/editor`)**: 
    - Craft compelling social media posts.
    - Utilize AI to enhance content and generate captions.
    - Choose from various themes, upload background images, and customize text and font styles.
    - Save and load custom templates.
    - Download your creations as PNG images.
3.  **Dev Studio (`/studio`)**: A simulated AI development environment where you can experiment with HTML, CSS, and JavaScript in a code editor with a live preview.
4.  **Admin Link Manager (`/admin`)**: Manage and add custom social links that appear on the contact section.

### Example: Creating a Social Media Post

1.  Navigate to the **Post Editor** view.
2.  Enter your desired content in the **Content** textarea.
3.  Click **AI Enhance** to refine your text or **Generate Caption** for social media-ready captions.
4.  Select a **Base Theme** or upload a **Background Image**.
5.  Customize **Text Color**, **Background Color**, and **Typography** as needed.
6.  (Optional) Save your design as a template for future use.
7.  Click **Download Template** to save your creation as a PNG image.

## 📂 Project Structure

```
Vercl.com/
├── public/
│   ├── manifest.json
│   └── index.css
├── src/
│   ├── components/
│   │   ├── ContactLinks.tsx
│   │   ├── DevStudio.tsx
│   │   ├── LinkManager.tsx
│   │   ├── Navbar.tsx
│   │   └── PostCreator.tsx
│   ├── services/
│   │   └── gemini.ts
│   ├── types.ts
│   ├── App.tsx
│   └── index.tsx
├── .env.local       # <-- Add your GEMINI_API_KEY here
├── index.html
├── package.json
├── README.md
├── tsconfig.json
└── vite.config.ts
```

## 📚 Dependencies

- `@google/genai`: For interacting with Google's Generative AI models.
- `react`, `react-dom`: Core React libraries for building the UI.
- `html2canvas`: For capturing DOM elements as images.
- `vite`, `@vitejs/plugin-react`: Build tools and React plugin.
- `typescript`, `@types/node`: TypeScript compiler and Node.js type definitions.

## 🔗 Important Links

- **Live Demo**: (Not explicitly provided, but deployable on Vercel)
- **GitHub Repository**: [https://github.com/rananisarsb51214-web/Vercl.com](https://github.com/rananisarsb51214-web/Vercl.com)
- **Author Profile**: [https://github.com/rananisarsb51214](https://github.com/rananisarsb51214)
- **AI Studio Link**: [https://ai.studio/apps/drive/1FGvvqm-D-0CxMp93lhPyO4My5zm9KJ85](https://ai.studio/apps/drive/1FGvvqm-D-0CxMp93lhPyO4My5zm9KJ85)

## 🤝 Contributing

Contributions are welcome! Please feel free to:

- Fork the repository.
- Create a new branch for your feature (`git checkout -b feature/AmazingFeature`).
- Commit your changes (`git commit -m 'Add some AmazingFeature'`).
- Push to the branch (`git push origin feature/AmazingFeature`).
- Open a Pull Request.

Please ensure your code adheres to the project's coding style and includes relevant tests if applicable.

## 📜 License

This project does not currently specify a license. Please refer to the repository owner for licensing details.

---

<div align="center">
  <p>
    Made with ❤️ by Rana51214
  </p>
  <p>
    <a href="https://github.com/rananisarsb51214-web/Vercl.com/fork" title="Fork repository">Fork</a> | <a href="https://github.com/rananisarsb51214-web/Vercl.com/stargazers" title="Star repository">Star</a> | <a href="https://github.com/rananisarsb51214-web/Vercl.com/issues" title="Open Issues">Report Issues</a>
  </p>
</div>


---
**<p align="center">Generated by [ReadmeCodeGen](https://www.readmecodegen.com/)</p>**