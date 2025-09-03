Certainly! Here is a comprehensive **README.md** for your project, **QualifAI**, based on the full tutorial, written in British English and formatted in Markdown.

***

# QualifAI – AI-Powered Applicant Tracking System

QualifAI is an enterprise-ready, AI-powered applicant tracking system (ATS) that allows you to upload, analyse, and manage CVs and job postings. Built with React, TypeScript, Tailwind CSS, and Puter.js, it leverages cutting-edge AI (including free GPT, Claude, and even Grok models) to deliver instant CV reviews, ATS scores, and custom feedback, all with a sleek, responsive user interface.

## Features

- **User Authentication** via Puter.js (no server-side configuration required)
- **Secure File Uploads** – Add CVs and job descriptions, all stored in the cloud
- **AI-Powered Analysis**:
  - Instant evaluation of CVs against job requirements
  - ATS score and detailed improvement suggestions
  - Supports complex job descriptions for highly targeted feedback
- **Real-Time Feedback** – Get actionable suggestions on style, content, structure, and skills
- **Database & Key-Value Store** – Track multiple CVs and job applications per user
- **Responsive UI** – Works beautifully on all devices
- **Zero Maintenance Costs** – End users cover their own costs via Puter’s unique infrastructure
- **Deployable on Puter or Vercel** – Goes live in seconds!

## Demo



***

## How it Works

1. **Register/Login:** Secure authentication with Puter.js.
2. **Upload CV & Job Info:** Fill in company name, job title, and paste the full job description. Upload your CV (PDF).
3. **Automated Analysis:** QualifAI converts your CV to an image, stores files securely, and invokes AI models for feedback.
4. **Instant Feedback:** Receive an overall ATS score, tips, and detailed category breakdown – tone, style, content, structure, skills.
5. **Iterate & Improve:** Use actionable feedback to strengthen your CV for each role.

***

## Tech Stack

- **Frontend:** React, React Router v7, TypeScript, Tailwind CSS v4
- **State Management:** Zustand
- **AI & Cloud:** Puter.js and Puter Cloud for authentication, file storage, AI tasks, and data management
- **PDF/Image Conversion:** pdfjs
- **Dev Tools:** WebStorm (free for non-commercial), Junie AI assistant for smart code suggestions
- **Deployment:** Easily deploy on Puter or any static hosting (Netlify, Vercel, GitHub Pages)

***

## Getting Started

### Prerequisites

- Node.js & npm
- A free [Puter.com](https://puter.com) account

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/qualifai.git
   cd qualifai
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Load assets:**
   - Download the asset kit (icons, images, etc.) from the original course (or use your own).
   - Unzip and place everything in the `/public` folder as instructed.

4. **Start development:**
   ```bash
   npm run dev
   ```

5. **Set up Puter:**
   - Register for a free Puter account (no credit card needed).
   - Adjust relevant configuration in `.env` or project files if needed.
   - Authentication and cloud storage integration are handled in the provided setup.

***

## Project Structure

```
qualifai/
├── app/
│   ├── components/             # UI Components (navbar, CV card, feedback, etc.)
│   ├── routes/                 # Page routes (Home, Upload, Feedback, Auth, etc.)
│   ├── lib/                    # Utility wrappers (Puter API, helpers)
│   ├── constants/              # Static data, mockups, AI format templates
│   └── types/                  # TypeScript types/declarations
├── public/                     # Static assets (images, icons, favicon)
├── utils/                      # Utility functions (formatting, helpers)
├── tailwind.config.js          # Tailwind CSS configuration
├── package.json
└── README.md                   # This file
```

***

## Major Components

- **Navbar:** Navigation bar for quick page switching and uploading new items.
- **CV Card:** Visual summary of each CV, including company role, image, and ATS score.
- **Upload Page:** Smart dropzone supporting drag-and-drop or click-to-upload; custom validation and progress.
- **Feedback Page:** Multi-category feedback display with expandable panels for each analysis category.
- **ATS Scorecard:** Instant visual indicator with suggestions for beating Applicant Tracking Systems.
- **Account Management:** Automated sign-in/out with real-time auth state tracking.
- **Wipe Data Utility:** For admins/developers to bulk delete all data during testing or development.

***

## Configuration & Customisation

- **British Spelling:** All output, UI labels, and documentation use British English.
- **Theme & Styles:** Customisable via Tailwind config and `app.css`.
- **AI Prompt/Response:** Tune feedback detail and structure via `/constants` and `/lib/puter.ts`.

***

## Deployment

### Deploy to Puter Cloud

1. Open your project in the Puter dev centre.
2. Build with:
   ```bash
   npm run build
   ```
3. Upload the contents of `build/client/` (not the folder itself) to Puter.
4. Follow the prompts to complete deployment.
5. Your app is now live at your Puter-provided URL!

### Deploy elsewhere

- The app is static and may be deployed to Vercel, Netlify, or GitHub Pages. Ensure SSR is off if deploying outside Puter.

***

## Contributing

Contributions are welcome! Please fork the repo and raise a Pull Request.

***

## Acknowledgements

- Original tutorial and code by [JavaScript Mastery](https://www.youtube.com/@javascriptmastery)
- AI models via Puter Cloud (GPT, Claude, Grok)
- Free assets and templates from the JS Mastery community

***

## Licence

This project is open-source under the MIT Licence.

***

**Build with passion. Analyse and improve your CVs for every job. Land your dream role with AI!**

