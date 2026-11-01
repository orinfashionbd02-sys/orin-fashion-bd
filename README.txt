ORIN FASHION BD setup:
1. firebase-config.js-এ PA​​STE_YOUR_FIREBASE_WEB_API_KEY_HERE জায়গায় Firebase Console > Project settings > General > Your apps থেকে আসল apiKey বসান।
2. এই ফাইলগুলো GitHub repository-র root-এ আপলোড করুন: index.html, style.css, app.js, admin.html, admin.js, firebase-config.js.
3. Authentication Email/Password enabled এবং admin user orinfashionbd02@gmail.com থাকতে হবে।
4. Admin page: আপনার সাইটের /admin.html ; Firebase Auth-এ সেট করা password ব্যবহার করুন।
5. Firestore Rules-এ orders fields এই app.js-এর সঙ্গে মেলে।
6. GitHub > Settings > Pages > Deploy from a branch > main > /(root) > Save.
7. Firebase Storage ব্যবহার করা হয়নি। পণ্যের ছবির জন্য HTTPS image URL দিন।
8. apiKey public web config; admin password কখনো ফাইলে লিখবেন না।
