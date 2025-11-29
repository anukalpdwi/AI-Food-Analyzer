<div align="center">
  <img width="1200" height="475" alt="Orbyt.food Banner" src="https://github.com/user-attachments/assets/0aa67016-6eaf-458a-adb2-6e31a0763ed6" />
  
  <h1>🍽️ Orbyt.food</h1>
  <p><strong>AI-Powered Nutritional Analysis from a Single Photo</strong></p>
  
  [![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
  [![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/)
  [![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)](https://vitejs.dev/)
  [![Google AI](https://img.shields.io/badge/Google_AI-4285F4?style=for-the-badge&logo=google&logoColor=white)](https://ai.google.dev/)
</div>

---

## 📖 Overview

**Orbyt.food** is an intelligent nutrition tracking application that leverages cutting-edge AI technology to analyze food images and provide comprehensive nutritional information. Simply snap a photo of your meal, and our AI identifies ingredients and calculates detailed macro breakdowns in seconds.

### ✨ Key Features

- **🤖 Instant AI Recognition** - Advanced computer vision identifies thousands of food items from complex dishes to raw ingredients
- **📊 Macro Breakdown** - Get detailed nutritional information including calories, protein, fat, and carbohydrates
- **🔍 Grounded Search** - Real-time web verification ensures accurate calorie counts using Google Search grounding
- **📈 Interactive Charts** - Beautiful, responsive donut charts for visualizing macronutrient distribution
- **🎨 Modern UI/UX** - Premium dark-mode interface with smooth animations and micro-interactions
- **🔒 Privacy-Focused** - Your data belongs to you with secure, local processing

---

## 🛠️ Tech Stack

### Core Technologies
- **[React 18.3](https://react.dev/)** - Modern UI framework with latest features
- **[TypeScript 5.8](https://www.typescriptlang.org/)** - Type-safe development
- **[Vite 6.2](https://vitejs.dev/)** - Lightning-fast build tool and dev server

### AI & Analysis
- **Advanced multimodal AI for vision and text processing** - 
- **Official Google Generative AI SDK** 

### UI & Visualization
- **[Framer Motion 11.0](https://www.framer.com/motion/)** - Production-ready animation library
- **[Recharts 2.12](https://recharts.org/)** - Composable charting library
- **[Lucide React](https://lucide.dev/)** - Beautiful, consistent icon set
- **[TailwindCSS Merge](https://github.com/dcastil/tailwind-merge)** - Utility-first styling

---

## 🚀 Getting Started

### Prerequisites

- **Node.js** (v18 or higher)
- **npm** (v9 or higher)
- **Google Gemini API Key** - Get one from [Google AI Studio](https://ai.google.dev/)

### Installation

1. **Clone the repository**
   ```bash
   git clone <your-repo-url>
   cd Food
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Configure API Key**
   
   Open `.env.local` and set your Gemini API key:
   ```env
   API_KEY=your_gemini_api_key_here
   ```

4. **Start the development server**
   ```bash
   npm run dev
   ```

5. **Open your browser**
   
   Navigate to `http://localhost:3000`

---

## 📱 Usage

1. **Upload an Image**
   - Click the upload area or drag and drop a food image
   - Supported formats: JPG, PNG, WEBP

2. **Analyze**
   - Click "Start Analysis" to process your image
   - The AI will identify the food and research nutritional data

3. **View Results**
   - See the identified food name with grounding sources
   - Review comprehensive nutritional summary
   - Explore interactive macro breakdown chart
   - View detailed calorie, protein, fat, and carb values

---

## 🏗️ Project Structure

```
Food/
├── index.html              # HTML entry point
├── index.tsx               # Main React application
├── package.json            # Dependencies and scripts
├── tsconfig.json           # TypeScript configuration
├── vite.config.ts          # Vite configuration
├── .env.local              # Environment variables (API keys)
└── README.md               # This file
```

---

## 🎨 Features Deep Dive

### AI-Powered Analysis Pipeline

1. **Food Identification** - Analyzes the image and identifies the food item
2. **Grounded Research** - Uses Google Search grounding to verify and enhance nutritional data
3. **Data Extraction** - Parses and structures nutritional information (calories, macros)
4. **Visual Presentation** - Renders results with interactive charts and detailed breakdowns

### Modern Design System

- **Glassmorphism Effects** - Frosted glass cards with blur effects
- **Gradient Accents** - Vibrant cyan and purple gradients
- **Micro-animations** - Smooth hover effects and transitions powered by Framer Motion
- **Responsive Layout** - Mobile-first design that scales beautifully

---

## 📦 Available Scripts

| Command | Description |
|---------|-------------|
| `npm run dev` | Start development server on port 3000 |
| `npm run build` | Build production bundle |
| `npm run preview` | Preview production build locally |

---

## 🔧 Configuration

### Environment Variables

Create a `.env.local` file in the root directory:

```env
API_KEY=your_google_gemini_api_key
```

## 🌐 Deployment

### Build for Production

```bash
npm run build
```

This creates an optimized production build in the `dist/` directory.

### Deploy to Vercel

```bash
# Install Vercel CLI
npm i -g vercel

# Deploy
vercel
```

### Deploy to Netlify

```bash
# Build the project
npm run build

# Deploy the dist/ folder to Netlify
```

**Important:** Remember to add your `API_KEY` environment variable in your hosting platform's settings.

---

## 🎯 Roadmap

- [ ] Meal history tracking and analytics
- [ ] Export nutrition data to CSV/PDF
- [ ] Integration with fitness trackers (Apple Health, Google Fit)
- [ ] Multi-language support
- [ ] Custom meal creation and saving
- [ ] Daily nutrition goals and tracking
- [ ] Recipe suggestions based on dietary preferences

---

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 🙏 Acknowledgments

- **Google Gemini AI** - For powering the vision analysis
- **Framer Motion** - For beautiful animations
- **Recharts** - For data visualization
- **Lucide** - For the icon library

---

## 📞 Support

If you encounter any issues or have questions:

- Open an issue on GitHub
- Check existing issues for solutions
- Ensure your API key is correctly configured

---

<div align="center">
  <strong>Built with ❤️ by Anukalp Dwivedi</strong>
  
  <p>⭐ Star this repo if you find it helpful!</p>
</div>
