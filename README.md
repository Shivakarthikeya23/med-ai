# 🩺 MedAI Diagnosis - Voice-Enabled Healthcare AI Platform

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![React](https://img.shields.io/badge/React-18.3.1-blue.svg)](https://reactjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.5.3-blue.svg)](https://www.typescriptlang.org/)
[![Supabase](https://img.shields.io/badge/Supabase-Latest-green.svg)](https://supabase.com/)

> **🏆 Healthcare AI Platform** - A revolutionary voice-enabled medical diagnosis application that combines cutting-edge AI with intuitive design to make healthcare more accessible and human-centered.

![MedAI Diagnosis Demo](https://images.unsplash.com/photo-1559757148-5c350d0d3c56?w=1200&h=600&fit=crop&crop=center)

## 🌟 Overview

MedAI Diagnosis is a comprehensive healthcare AI platform that enables users to upload medical images and describe symptoms using natural voice input. The AI analyzes both visual and audio data to provide preliminary medical assessments with voice responses, creating a more natural and accessible healthcare experience.

### 🎯 Key Innovation
- **Voice-First Interface**: Natural conversation flow with AI doctor
- **Multimodal AI**: Combines image analysis with voice interaction
- **Complete Patient Journey**: From diagnosis to follow-up tracking
- **Production-Ready**: HIPAA-compliant with enterprise security

## ✨ Features

### 🎤 Voice-Enabled Diagnosis
- **Natural Speech Input**: Describe symptoms in your own words
- **AI Voice Response**: Get spoken feedback from the AI doctor
- **Real-time Transcription**: Powered by GROQ Whisper API
- **High-Quality TTS**: ElevenLabs integration for natural voice synthesis

### 📸 Medical Image Analysis
- **Multi-format Support**: X-rays, CT scans, MRIs, ultrasounds
- **AI-Powered Analysis**: Google Gemini Vision API integration
- **Confidence Scoring**: Transparent AI assessment reliability
- **Instant Processing**: Results in seconds, not hours

### 📋 Complete Patient Management
- **Follow-up System**: Track patient progress and treatment updates
- **Status Management**: Pending, In Progress, Resolved workflows
- **Professional Reports**: PDF generation with medical formatting
- **Audit Trail**: Complete activity logging for compliance

### 🔒 Enterprise Security
- **HIPAA Compliance**: Encrypted data storage and transmission
- **User Isolation**: Row-level security with Supabase
- **Audit Logging**: Complete activity tracking
- **Secure Storage**: Medical images in protected cloud storage

### 📱 Modern User Experience
- **Responsive Design**: Works on mobile, tablet, and desktop
- **Beautiful UI**: Apple-level design aesthetics
- **Smooth Animations**: Framer Motion micro-interactions
- **Accessibility**: Voice interface removes barriers

## 🚀 Quick Start

### Prerequisites
- Node.js 18+ and npm
- Supabase account
- API keys for:
  - Google Gemini API
  - GROQ API (for speech processing)
  - ElevenLabs API (for voice synthesis)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Shivakarthikeya23/med-ai.git
   cd medai-diagnosis
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   ```bash
   cp .env.example .env
   ```
   
   Fill in your API keys:
   ```env
   # Supabase Configuration
   VITE_SUPABASE_URL=your_supabase_url_here
   VITE_SUPABASE_ANON_KEY=your_supabase_anon_key_here

   # Google Gemini API Configuration
   VITE_GEMINI_API_KEY=your_gemini_api_key_here

   # GROQ API Configuration
   VITE_GROQ_API_KEY=your_groq_api_key_here

   # ElevenLabs API Configuration
   VITE_ELEVENLABS_API_KEY=your_elevenlabs_api_key_here
   ```

4. **Set up Supabase**
   - Create a new Supabase project
   - Run the migrations in the `supabase/migrations` folder
   - Create a storage bucket named `medical-images`
   - Configure Row Level Security policies

5. **Start the development server**
   ```bash
   npm run dev
   ```

6. **Open your browser**
   Navigate to `http://localhost:5173`

## 🏗️ Architecture

### Frontend Stack
- **React 18** with TypeScript
- **Tailwind CSS** for styling
- **Framer Motion** for animations
- **React Router** for navigation
- **Lucide React** for icons

### Backend & Services
- **Supabase** for database and authentication
- **Supabase Storage** for medical image storage
- **Google Gemini API** for image analysis
- **GROQ API** for speech-to-text
- **ElevenLabs API** for text-to-speech

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guidelines](CONTRIBUTING.md) for details.

### Development Workflow
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Add tests if applicable
5. Submit a pull request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

