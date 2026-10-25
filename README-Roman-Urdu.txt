ROYAL LAW COLLEGE MINI APP — ANDROID GUIDE

Yeh folder website ko installable mini-app (PWA) banata hai.

ONLINE PUBLISH KARNE KA TAREEQA:
1. GitHub par apni repository kholen.
2. ZIP ko mobile mein extract karein.
3. Is folder ki tamam files repository ke root mein upload karein:
   index.html, manifest.webmanifest, service-worker.js, icon-192.png, icon-512.png
4. GitHub repository Settings > Pages mein ja kar branch (aksar main) aur /(root) select karke Save karein.
5. Website HTTPS link par kholen.
6. Android Chrome mein menu (⋮) > Install app ya Add to Home screen par tap karein.

AHAM:
- Offline shell cache ho sakta hai; pehli dafa online publish/install ke liye internet zaroori hai.
- AI section filhal sawal ChatGPT mein kholta hai. Website ke andar direct AI jawab dikhane ke liye secure backend/API deploy karna alag se zaroori hai.
- GitHub Pages static frontend host karta hai; backend ZIP ko GitHub Pages par rakhne se backend run nahi hota.
