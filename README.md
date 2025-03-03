# Sabeel - Your Ramadan Companion 🌙

Sabeel is a comprehensive Islamic web application designed to enhance your Ramadan experience. The name "سبیل" (Sabeel) means "path" or "way" in Arabic, reflecting our goal to help users stay connected with their spiritual journey.

## Features ✨

### 1. Quran Reading & Progress Tracking
- Interactive Quran reading timer
- Group reading progress tracking
- Personal reading statistics and streaks
- Random verse display for daily reflection

### 2. Prayer Times & Namaz Tracking
- Accurate prayer times based on location
- Prayer completion tracking
- Weekly prayer statistics
- Custom prayer notifications

### 3. Islamic Content Lookup
- Quran verse search with translations
- Hadith search functionality
- Tafsir (Quranic interpretation) access
- Multiple language support

### 4. Group Features
- Create and join reading groups
- Track group progress
- Invite friends and family
- Competitive leaderboards

### 5. User Profiles
- Personal reading statistics
- Achievement tracking
- Goal setting
- Activity history

## Tech Stack 🛠️

- **Frontend**: Next.js, React, TypeScript
- **UI Components**: Radix UI, Tailwind CSS
- **Authentication**: Firebase Auth
- **Database**: Firebase Firestore
- **APIs**: 
  - Prayer Times API
  - Quran API
  - Hadith API

## UI Images

<div align="center">
  <img src="https://github.com/user-attachments/assets/c3772ebd-0448-40c0-837b-fcdbc158b1af" width="400" alt="Sabeel UI 1" />
  <img src="https://github.com/user-attachments/assets/d8b29e5f-9ab3-43bf-a190-90482ad3e935" width="400" alt="Sabeel UI 2" />
  <img src="https://github.com/user-attachments/assets/fe8ddd1a-b555-4bf3-8735-fb136847931a" width="400" alt="Sabeel UI 3" />
  <img src="https://github.com/user-attachments/assets/2b3c706f-7a39-4ed9-848c-672563724e28" width="400" alt="Sabeel UI 4" />
  <img src="https://github.com/user-attachments/assets/36be68cf-afb1-4775-9cd4-295f454225e3" width="400" alt="Sabeel UI 5" />
  <img src="https://github.com/user-attachments/assets/a09d6ee3-583d-4308-bdd5-01c71df83fe4" width="400" alt="Sabeel UI 6" />
  <img src="https://github.com/user-attachments/assets/10671bb4-b726-480b-aca0-e070e90f8871" width="400" alt="Sabeel UI 7" />
</div>

## Getting Started 🚀

1. Clone the repository:
```bash
cd sabeel
```

2. Install dependencies:
```bash
npm install
```

3. Set up Firebase:
   - Create a Firebase project
   - Enable Authentication and Firestore
   - Copy your Firebase config
   - Create a `.env.local` file with your Firebase credentials

4. Run the development server:
```bash
npm run dev
```

5. Open [http://localhost:3000](http://localhost:3000) in your browser

## Environment Variables 🔑

Create a `.env.local` file with the following variables:
```
NEXT_PUBLIC_FIREBASE_API_KEY=your_api_key
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your_auth_domain
NEXT_PUBLIC_FIREBASE_PROJECT_ID=your_project_id
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=your_storage_bucket
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=your_messaging_sender_id
NEXT_PUBLIC_FIREBASE_APP_ID=your_app_id
NEXT_PUBLIC_FIREBASE_MEASUREMENT_ID=your_measurement_id
```

## Deployment on Render 🚀

### Build and Run Commands

For deployment on Render, use the following configuration:

- **Build Command:**
```bash
npm install && npm run build
```

- **Start Command:**
```bash
npm start
```

### Environment Setup

1. In your Render dashboard, create a new Web Service
2. Connect your GitHub repository
3. Choose the branch you want to deploy
4. Set the following:
   - **Runtime**: Node
   - **Build Command**: `npm install && npm run build`
   - **Start Command**: `npm start`
5. Add all your environment variables from `.env.local` to Render's environment variables section
6. Deploy your application

### Auto-Deploy Configuration

Render automatically deploys your application when you push to your repository. To ensure smooth deployments:

1. Ensure your `package.json` includes:
```json
{
  "scripts": {
    "dev": "next dev",
    "build": "next build",
    "start": "next start",
    "lint": "next lint"
  }
}
```

2. Make sure all dependencies are listed in your `package.json`
3. Set Node version in `package.json`:
```json
{
  "engines": {
    "node": ">=18.x"
  }
}
```

## Contributing 🤝

We welcome contributions! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License 📝

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments 🙏

- Quran API provided by [Quran.com API](https://quran.api-docs.io/)
- Prayer times calculations based on reliable astronomical calculations
- UI components from [shadcn/ui](https://ui.shadcn.com/)
- Icons from [Lucide](https://lucide.dev/)

---

Made with ❤️ for the Muslim community
