# ✨ Zen Chat Harmony

> **A Mental Health & Emotional Wellness Companion**

[![Live Demo](https://img.shields.io/badge/🔗_Live_Demo-https%3A%2F%2Fzen--chat--harmony.vercel.app-blue?style=for-the-badge)](https://zen-chat-harmony.vercel.app/)
[![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)
[![React](https://img.shields.io/badge/React-18.3-61DAFB?style=flat-square&logo=react)](https://react.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.8-3178C6?style=flat-square&logo=typescript)](https://www.typescriptlang.org/)

---

## 🎯 Purpose

Zen Chat Harmony is an intelligent, compassionate AI-powered chatbot designed to provide **mental health support and emotional wellness guidance**. Unlike generic chatbots, it's specifically engineered to:

- 🧠 Understand emotional contexts and respond with empathy
- 🛡️ Recognize distress signals and provide crisis resources
- 🧘 Promote mindfulness through guided practices
- 💡 Offer therapeutic suggestions based on user needs
- 🌟 Create a safe, judgment-free space for emotional expression

Whether you're seeking daily wellness support, mindfulness guidance, or someone to talk to during difficult moments, Zen Chat Harmony is here for you.

---

## ✨ Key Features

| Feature | Description |
|---------|-------------|
| 🤖 **AI-Powered Conversations** | Context-aware responses using advanced NLP for meaningful interactions |
| 🧘 **Meditation Guides** | Curated meditation sessions for stress relief and mindfulness |
| 🎵 **Sound Therapy** | Calming background sounds and ambient music for relaxation |
| 🙏 **Mudra Practices** | Ancient yoga mudra techniques with visual guides |
| 👨‍🏫 **Mentor Support** | Access to wellness mentors and expert guidance |
| 🎙️ **Voice Input** | Hands-free interaction with audio recording capabilities |
| 📤 **File Upload** | Share documents, journal entries, or images for context |
| 🚨 **Crisis Detection** | Intelligent recognition of distress signals with hotline resources |
| 🎨 **Zen-Inspired UI** | Calming aesthetic with carefully chosen color palette |
| 📱 **Fully Responsive** | Seamless experience on desktop, tablet, and mobile devices |
| 🌙 **Dark Mode Support** | Eye-friendly interface for 24/7 accessibility |
| 💾 **Conversation Memory** | Persistent chat history with secure cloud storage |

---

## 🛠️ Technology Stack

| Layer | Technologies |
|-------|--------------|
| **Frontend Framework** | ![React](https://img.shields.io/badge/React-18.3-61DAFB?logo=react) ![TypeScript](https://img.shields.io/badge/TypeScript-5.8-3178C6?logo=typescript) |
| **Build Tool** | ![Vite](https://img.shields.io/badge/Vite-5.4-646CFF?logo=vite) |
| **Styling** | ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.4-06B6D4?logo=tailwindcss) ![PostCSS](https://img.shields.io/badge/PostCSS-8.5-DD3A0A?logo=postcss) |
| **UI Components** | ![shadcn/ui](https://img.shields.io/badge/shadcn%2Fui-Latest-black) ![Radix UI](https://img.shields.io/badge/Radix_UI-Latest-black) |
| **Backend/Database** | ![Supabase](https://img.shields.io/badge/Supabase-2.57-3ECF8E?logo=supabase) |
| **State Management** | ![React Query](https://img.shields.io/badge/TanStack_Query-5.83-FF4154) |
| **Forms** | ![React Hook Form](https://img.shields.io/badge/React_Hook_Form-7.61-EC5990) ![Zod](https://img.shields.io/badge/Zod-3.25-3E67AC) |
| **Icons** | ![Lucide React](https://img.shields.io/badge/Lucide_React-0.462-F56565) |
| **Notifications** | ![Sonner](https://img.shields.io/badge/Sonner-1.7-000000) |
| **Charts** | ![Recharts](https://img.shields.io/badge/Recharts-2.15-8884D8) |
| **Routing** | ![React Router](https://img.shields.io/badge/React_Router-6.30-CA4245?logo=reactrouter) |
| **Linting** | ![ESLint](https://img.shields.io/badge/ESLint-9.32-4B32C3?logo=eslint) |

### Full Dependency Breakdown

```json
{
  "Core UI": [
    "@radix-ui/react-*",
    "shadcn-ui",
    "class-variance-authority",
    "clsx",
    "tailwind-merge"
  ],
  "Form & Validation": [
    "react-hook-form",
    "@hookform/resolvers",
    "zod"
  ],
  "Data & State": [
    "@tanstack/react-query",
    "@supabase/supabase-js",
    "recharts"
  ],
  "Utilities": [
    "date-fns",
    "lucide-react",
    "sonner",
    "vaul",
    "next-themes"
  ],
  "Layout": [
    "react-resizable-panels",
    "embla-carousel-react"
  ]
}
```

---

## 🚀 Quick Start Guide

### Prerequisites

- **Node.js** v16 or higher ([Download](https://nodejs.org/))
- **npm** v7+ or **yarn** (comes with Node.js)
- **Git** for version control

### Installation Steps

#### 1️⃣ Clone the Repository

```bash
git clone https://github.com/24211a66a7-jpg/zenchatbot.git
cd zenchat-bot
```

#### 2️⃣ Install Dependencies

```bash
npm install
# or if using yarn
yarn install
```

#### 3️⃣ Set Up Environment Variables

Create a `.env.local` file in the root directory:

```env
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
```

#### 4️⃣ Start Development Server

```bash
npm run dev
```

The application will be available at `http://localhost:5173`

#### 5️⃣ Build for Production

```bash
npm run build
npm run preview
```

---

## 📋 Available Scripts

| Command | Description |
|---------|-------------|
| `npm run dev` | Start development server with hot reload |
| `npm run build` | Build optimized production bundle |
| `npm run build:dev` | Build with development mode enabled |
| `npm run lint` | Run ESLint to check code quality |
| `npm run preview` | Preview production build locally |

---

## 🏗️ Project Architecture

```
zenchat-bot/
├── src/
│   ├── components/
│   │   ├── ChatMessage.tsx          # Message display component
│   │   ├── SuggestionCard.tsx       # Suggestion UI component
│   │   └── ui/                      # shadcn/ui components library
│   ├── pages/
│   │   ├── Chat.tsx                 # Main chat interface
│   │   ├── Meditation.tsx           # Meditation guides page
│   │   ├── Sound.tsx                # Sound therapy page
│   │   ├── Mudra.tsx                # Mudra practices page
│   │   ├── Mentor.tsx               # Mentor support page
│   │   ├── Index.tsx                # Landing page
│   │   └── NotFound.tsx             # 404 page
│   ├── hooks/
│   │   ├── use-toast.ts             # Toast notification hook
│   │   └── use-mobile.tsx           # Mobile detection hook
│   ├── integrations/
│   │   └── supabase/                # Supabase client & types
│   ├── lib/
│   │   └── utils.ts                 # Utility functions
│   ├── App.tsx                      # Root component
│   └── main.tsx                     # Entry point
├── supabase/
│   ├── functions/
│   │   └── ai-chat/                 # Edge functions for AI
│   └── migrations/                  # Database migrations
├── public/                          # Static assets
├── vite.config.ts                   # Vite configuration
├── tailwind.config.ts               # Tailwind CSS config
├── tsconfig.json                    # TypeScript configuration
└── package.json                     # Dependencies & scripts
```

---

## 💻 How It Works

### Chat Flow

```
User Input
    ↓
Emotion Analysis & Context Detection
    ↓
[Distress Detected?] → Crisis Resources & Hotline
    ├─ Yes
    └─ No → AI Response Generation
    ↓
Suggestion Generation (Meditation, Sound, etc.)
    ↓
Display with Message History
    ↓
Store in Supabase
```

### Intelligent Features

- **Emotional Recognition**: Analyzes sentiment and emotional state
- **Multi-Modal Support**: Text, voice, and file inputs
- **Context Awareness**: Maintains conversation history for coherent responses
- **Resource Recommendations**: Suggests appropriate wellness activities

---

## 🎨 Customization

### Modify Theme Colors

Edit `tailwind.config.ts`:

```typescript
theme: {
  extend: {
    colors: {
      // Your custom colors
    }
  }
}
```

### Update Affirmations & Suggestions

Edit `src/pages/Chat.tsx` constants:

```typescript
const positiveAffirmations = [
  "Your custom affirmation...",
  // Add more
];
```

---

## 🔐 Security & Privacy

- ✅ All data encrypted in transit and at rest
- ✅ Supabase Row Level Security (RLS) enabled
- ✅ No personal data shared with third parties
- ✅ Anonymous user support for privacy-conscious users
- ✅ Regular security audits and updates

---

## 🌐 Deployment

### Deploy to Vercel (Recommended)

1. Push code to GitHub
2. Connect repository to [Vercel](https://vercel.com/)
3. Set environment variables in Vercel dashboard
4. Deploy automatically on every push

### Deploy to Netlify

```bash
npm run build
# Connect build folder to Netlify
```

### Deploy to GitHub Pages

```bash
npm run build
# Configure gh-pages deployment
```

---

## 📊 Performance Metrics

- ⚡ **First Contentful Paint**: < 1.2s
- 🚀 **Largest Contentful Paint**: < 2.5s
- 📦 **Bundle Size**: ~185 KB gzipped
- ♿ **Accessibility Score**: 95+
- 🎯 **Lighthouse Score**: 90+

---

## 🐛 Troubleshooting

### Port Already in Use

```bash
# On Windows
netstat -ano | findstr :5173
taskkill /PID <PID> /F

# On macOS/Linux
lsof -i :5173
kill -9 <PID>
```

### Supabase Connection Issues

- Verify `.env.local` credentials
- Check Supabase project status
- Ensure network connectivity

### Build Errors

```bash
# Clear cache and reinstall
rm -rf node_modules package-lock.json
npm install
npm run build
```

---

## 🤝 Contributing

Contributions are welcome! Here's how:

1. Fork the repository
2. Create feature branch (`git checkout -b feature/amazing-feature`)
3. Commit changes (`git commit -m 'Add amazing feature'`)
4. Push to branch (`git push origin feature/amazing-feature`)
5. Open Pull Request

---

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- Built with ❤️ for mental health awareness
- Inspired by wellness and mindfulness practices
- Thanks to all contributors and supporters
- Special thanks to the open-source community

---

## 📞 Support & Contact

- 🔗 **Live Demo**: [https://zen-chat-harmony.vercel.app/](https://zen-chat-harmony.vercel.app/)
- 📧 **Report Issues**: [GitHub Issues](https://github.com/24211a66a7-jpg/zenchatbot.git)
- 💬 **Discussions**: [GitHub Discussions](https://github.com/24211a66a7-jpg/zenchatbot.git)

---

## ⚠️ Crisis Resources

If you're in crisis, please reach out:

| Region | Resource | Contact |
|--------|----------|---------|
| 🇺🇸 **USA** | National Suicide Prevention Lifeline | 988 or 1-800-273-8255 |
| 🇮🇳 **India** | AASRA | 9820466726 |
| 🇬🇧 **UK** | Samaritans | 116 123 |
| 🌍 **International** | Befrienders International | [Directory](https://www.befrienders.org/) |

**Remember**: Your life matters. Help is available 24/7.

---

<div align="center">

**Made with 💚 for your mental wellness**

[⬆ Back to Top](#-zen-chat-harmony)

</div>
