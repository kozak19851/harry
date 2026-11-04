HARRY – APK BEZ ANDROID STUDIO (przez GitHub, za darmo)

1. Załóż konto na github.com i utwórz nowe repozytorium (New repository).
2. Rozpakuj ten ZIP. Wgraj WSZYSTKIE pliki do repozytorium
   (Add file > Upload files), razem z folderami www i .github.
3. Wejdź w zakładkę Actions. Budowanie startuje samo (ok. 5-8 minut).
   Jeśli nie, wybierz "Build APK" > Run workflow.
4. Po zakończeniu otwórz przebieg i pobierz plik "harry-apk" (ZIP z app-debug.apk).
5. Wyślij app-debug.apk na telefon, otwórz go i zainstaluj
   (zezwól na instalację z nieznanych źródeł).

ALTERNATYWA – lokalnie: Node.js 18+, Android Studio, JDK 17:
   npm install; npx cap add android; npx cap sync android; npx cap open android
   Build > Build APK(s)
