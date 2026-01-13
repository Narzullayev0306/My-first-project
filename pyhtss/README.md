# 📱 TOPIK AI Coach (MVP Demo)

Mobile-first TOPIK II preparation MVP with a Writing Lab, gamification, store, and demo payment flows. This is a single-page Flask app that simulates the required onboarding flow and app shell UI.

## ✅ Core UX Flow (Demo)

1. Splash screen
2. Auth gate (login/register)
3. Profile setup wizard (required)
4. Main app shell with bottom navigation

## ✨ Features Included (Front-end MVP)

- Full-screen mobile app shell layout
- Bottom tab navigation (Overview, Practice, Writing Lab, Store, Profile)
- Profile setup wizard with username validation and avatar/photo preview
- UI + explanation language toggles (UZ/RU/EN)
- Dark/Light theme toggle
- Writing Lab with prompt selection and AI feedback placeholder
- Gamification (XP, level, title, coins, streak)
- Store with demo inventory + coin purchases
- Demo wallet with Stripe/Local Cards/Crypto payment flows (sandbox only)
- PWA manifest + service worker for offline shell

## 🚀 Run Locally

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

2. Start the app:
   ```bash
   python app.py
   ```

3. Open in your browser:
   ```
   http://localhost:5000
   ```

## 📂 Project Structure

```
pyhtss/
├── app.py
├── templates/
│   └── index.html
├── static/
│   ├── style.css
│   ├── manifest.json
│   ├── service-worker.js
│   └── icons/
│       └── icon.svg
└── README.md
```

## ⚠️ Notes

- This MVP uses localStorage for demo state (auth/profile/coins).
- Payment providers are demo-only and do not process real payments.
- Use it as a UI/UX prototype for a full Next.js + Supabase build.

---

Built for TOPIK II preparation and Writing Lab workflow demos.
