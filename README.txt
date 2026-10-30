STUDENT APP - SETUP (Flutter)

1. flutter create student_app
2. cd student_app
3. flutter pub add http
4. Is zip ka "lib" folder copy karke project ke "lib" folder ko replace karo.
5. lib/services/api_service.dart me PASTE_YOUR_WEB_APP_URL_HERE ki jagah
   apna Apps Script /exec URL paste karo.
6. android/app/src/main/AndroidManifest.xml me <application> tag ke
   just upar ye line add karo:
   <uses-permission android:name="android.permission.INTERNET"/>
7. flutter run
8. Release APK: flutter build apk --release
   (build/app/outputs/flutter-apk/app-release.apk)
