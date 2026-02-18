# Resumind - AI Resume Analyzer

An intelligent platform that analyzes resumes against job descriptions to provide actionable feedback, ATS scores, and improvement tips.

## Features

- **AI Feedback**: Detailed analysis of your resume content, structure, and skills.
- **ATS Scoring**: Get a realistic ATS compatibility score for specific job titles.
- **Visual Insights**: Dynamic score gauges and summaries for quick assessment.
- **PDF Processing**: Seamless PDF-to-image conversion for AI vision analysis.
- **Modern UI**: Clean, responsive interface built with Tailwind CSS 4.

## Tech Stack

- **Framework**: [React Router 7](https://reactrouter.com/) (Vite-based)
- **Backend / Cloud**: [Puter.js](https://puter.com/) (Authentication, FS, KV, AI)
- **State Management**: [Zustand](https://zustand.docs.pmnd.rs/)
- **Styling**: [Tailwind CSS 4](https://tailwindcss.com/)
- **PDF Library**: [PDF.js](https://mozilla.github.io/pdf.js/)

## Getting Started

### 1. Installation
```bash
npm install
```

### 2. Development
```bash
npm run dev
```

### 3. Build
```bash
npm run build
```

## Project Structure

- `app/routes/`: Main application pages (`home`, `upload`, `resume`).
- `app/components/`: Reusable UI components (`ScoreGauge`, `FileUploader`, `Navbar`).
- `app/lib/`: Custom utilities and library integrations.
- `public/`: Static assets and PDF.js worker.

