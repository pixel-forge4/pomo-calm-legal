# Pomo Calm - Google Play listing kit (v2, free + ads, no Pro)

## App name (max 30 chars)
Pomo Calm: Focus Timer

## Short description (max 80 chars)
EN: Calm Pomodoro timer with ambient sounds, goals, streaks and achievements.
AR: مؤقت بومودورو هادئ بأصوات محيطة وأهداف وإنجازات وتتبع للتقدم.
FR: Minuteur Pomodoro apaisant : sons d'ambiance, objectifs, séries et succès.

## Full description - English
Pomo Calm helps you focus with the Pomodoro technique, calmly and without clutter.

- Focus sessions, short breaks and a long break every 4 sessions, with durations you set
- Intentions: write what you are focusing on and see it in your history
- Progress: today's minutes, a 7-day chart and a history of your sessions
- Achievements for sessions, total focus time and focus streaks
- Daily goal with a progress bar, and a streak counter to keep you coming back
- Optional daily reminder at the time you choose
- Ambient sounds that work offline: white noise, wind and waves (free), plus rain, fire and deep tones (unlock for the day by watching a short ad)
- Calm backgrounds, and your own photo as a background (unlock for the day by watching a short ad)
- A notification when a session ends, even if the screen is off
- English, Arabic and French

Free with light ads. No account needed. Your sessions and settings stay on your device.

## Full description - Arabic
يساعدك Pomo Calm على التركيز بتقنية بومودورو، بهدوء ودون تشويش.

- جلسات تركيز، واستراحات قصيرة، واستراحة طويلة كل 4 جلسات، بمدد تحددها أنت
- النيّات: اكتب على ماذا تركز وشاهدها في سجلك
- التقدم: دقائق اليوم، ورسم لآخر 7 أيام، وسجل بجلساتك
- إنجازات للجلسات ومجموع وقت التركيز وأيام التركيز المتتالية
- هدف يومي بشريط تقدم، وعدّاد أيام متتالية يشجعك على العودة
- تذكير يومي اختياري في الوقت الذي تختاره
- أصوات محيطة تعمل بدون إنترنت: ضجيج أبيض ورياح وأمواج (مجانية)، ومطر ونار ونغمات عميقة (تُفتح ليوم كامل بمشاهدة إعلان قصير)
- خلفيات هادئة، وصورتك الخاصة كخلفية (تُفتح ليوم كامل بمشاهدة إعلان قصير)
- إشعار عند انتهاء الجلسة، حتى والشاشة مطفأة
- الإنجليزية والعربية والفرنسية

مجاني مع إعلانات خفيفة. لا حاجة لحساب. جلساتك وإعداداتك تبقى على جهازك.

## Full description - French
Pomo Calm vous aide à vous concentrer avec la technique Pomodoro, calmement et sans fioritures.

- Sessions de concentration, pauses courtes et longue pause toutes les 4 sessions, avec les durées de votre choix
- Intentions : notez sur quoi vous vous concentrez et retrouvez-le dans votre historique
- Progrès : minutes du jour, graphique des 7 derniers jours et historique des sessions
- Succès pour les sessions, le temps de concentration total et les séries de jours
- Objectif quotidien avec barre de progression et compteur de série pour vous donner envie de revenir
- Rappel quotidien facultatif à l'heure de votre choix
- Sons d'ambiance hors ligne : bruit blanc, vent et vagues (gratuits), puis pluie, feu et tons graves (à débloquer pour la journée en regardant une courte pub)
- Fonds apaisants, et votre propre photo en arrière-plan (à débloquer pour la journée en regardant une courte pub)
- Notification à la fin de chaque session, même écran éteint
- Anglais, arabe et français

Gratuit avec publicités discrètes. Aucun compte requis. Vos sessions et réglages restent sur votre appareil.

## Graphics to prepare
- App icon: 512 x 512 PNG
- Feature graphic: 1024 x 500 PNG/JPG
- Phone screenshots: at least 2 (timer, progress, achievements, settings)

## Play Console > Store settings
- App or game: App
- Category: Productivity
- Free or paid: Free
- Contact email: Cmr734068@gmail.com
- Privacy policy URL: https://pixel-forge4.github.io/pomo-calm-legal/privacy.html
  (use your real GitHub username and repository name if they differ)
- Terms of use (optional, you can add it to the description or website):
  https://pixel-forge4.github.io/pomo-calm-legal/terms.html

## Play Console > App content (answers match what the app really does)
- App access: all functionality is available without login or special access
- Ads: Yes, the app contains ads (Google AdMob: banner, interstitial, rewarded)
- Content rating: answer the IARC questionnaire honestly (no violence, sexual
  content, gambling, user-generated content, location sharing or purchases)
- Target audience: 13+ (do NOT select under 13; the app is not for children)
- Data safety:
  - Data collected and shared by the Google Mobile Ads SDK (per Google's AdMob
    disclosure guide, check it again when you fill the form):
    * Approximate location (derived from IP address)
    * App interactions (launches, taps, video views)
    * Diagnostics (app and SDK performance)
    * Device or other IDs (advertising ID, app set ID)
  - Purposes: advertising or marketing, analytics, fraud prevention
  - These are optional for the user (consent form, ad ID controls)
  - Data is encrypted in transit: Yes
  - Everything else (settings, session history, intentions, achievements,
    background photo) stays on the device and is not collected
  - No account, so no account-deletion flow is needed
- Advertising ID: Yes, the app uses it (AdMob)
- Foreground service (type: media playback): the app plays ambient sounds
  while the user focuses
- Exact alarms (USE_EXACT_ALARM): the core function of the app is a timer, and
  exact alarms deliver the end-of-session notification on time
- Not applicable: news app, government, financial features, health features

## Release order
1. Test the debug APK from GitHub Actions (timer, sounds, notification, ads)
2. Create the keystore, add the 4 Secrets, run Release AAB
3. Host privacy.html and terms.html (public GitHub Pages) and add the URL
4. Create the app in Play Console, fill listing and App content, upload the AAB
   to Internal testing
5. If your personal developer account needs it, run a Closed test with at least
   12 testers for 14 days, then apply for Production
6. After the app is live, link it in AdMob and set up the consent message in
   AdMob > Privacy and messaging

## Notes
- No in-app purchases. Google does not currently support merchant registration
  for developers located in Morocco, so the app is free with ads only.
- New apps must target the API level Google requires (the project targets 36).
- You are responsible for the legal text. Have a lawyer review the terms if you
  want certainty, especially the governing-law clause.
