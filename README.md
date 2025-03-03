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