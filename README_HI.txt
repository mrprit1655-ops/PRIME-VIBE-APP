PRIME VIBE – Android Studio Project (Demo)

इस ZIP में PRIME VIBE के मौजूदा salon + shopping demo को Android ऐप shell में रखा गया है।

APK बनाने के लिए:
1. कंप्यूटर पर Android Studio इंस्टॉल करें।
2. Android Studio में इस ZIP को Extract करके "Open" करें।
3. Gradle Sync पूरा होने दें और Android SDK 35 इंस्टॉल करें।
4. ऊपर Build > Build Bundle(s) / APK(s) > Build APK(s) चुनें।
5. APK का आउटपुट app/build/outputs/apk/debug/app-debug.apk में मिलेगा।
6. APK अपने Android फोन में भेजकर इंस्टॉल करें (फोन में "Install unknown apps" की अनुमति लग सकती है)।

जरूरी सीमाएँ:
- यह शुरुआती डेमो है; डेटा फिलहाल फोन/ऐप के स्थानीय स्टोरेज में रहता है।
- असली OTP login, secure owner-only admin, cloud database, UPI payment gateway,
  WhatsApp alerts, courier tracking और multi-device sync अभी जुड़े नहीं हैं।
- Play Store पर डालने से पहले production backend, privacy policy, app signing,
  testing और Google Play Developer account की जरूरत होगी।
- Google Play पर पब्लिश करने के लिए अपने अकाउंट का उपयोग करें; पासवर्ड/OTP किसी से साझा न करें।


GitHub Actions se APK build:
- Project ke saare extracted files GitHub repository ke main branch me upload karein.
- Actions tab me Build PRIME VIBE APK workflow select karke Run workflow karein.
- Build complete hone par workflow run ke Artifacts section se PRIME-VIBE-debug-apk download karein.
