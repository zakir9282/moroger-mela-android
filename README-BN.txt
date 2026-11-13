মোরগের মেলা Android WebView Wrapper

এই প্রজেক্টটি একটি Android অ্যাপের নিজস্ব Activity-র মধ্যে মোরগের মেলার ওয়েব অ্যাপ চালায়।
Chrome-এর address bar বা browser UI দেখায় না। ফোনের Back চাপলে WebView-এর আগের পেজে যায়।

গুরুত্বপূর্ণ:
- এটি Native WebView shell; মোরগের মেলার মূল হিসাব/লগইন/ব্যাকএন্ড এখনো ওয়েব সার্ভিস থেকেই চলে।
- Google Drive OAuth বা biometric-এর মতো browser-specific ফিচার WebView-তে আলাদা পরীক্ষা প্রয়োজন; সব ফিচার কাজ করবে বলে এখনই নিশ্চয়তা দেওয়া যাচ্ছে না।
- App icon এখনো আসল ব্যবহারকারীর লোগো দিয়ে প্রতিস্থাপন করা হয়নি; এই কথোপকথনের ফাইল-স্টোরে আগের লোগোর binary পাওয়া যায়নি।
- এই ZIP নিজে APK নয়। AndroidIDE-তে Gradle project হিসেবে খুলে Build APK করতে হবে।

Build:
1. ZIP Extract করুন।
2. AndroidIDE-তে extracted MorogerMela folder খুলুন।
3. Gradle sync শেষ হতে দিন।
4. Build > Assemble Debug APK চালান।
5. app/build/outputs/apk/debug/app-debug.apk তৈরি হলে সেটি ফোনে ইনস্টল করে পরীক্ষা করুন।

Package ID: bd.morogermela.app
App name: মোরগের মেলা
Website: https://app-sv1cug.v2.appdeploy.ai/
