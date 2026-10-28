TURBO & VÄNNER – FIX FÖR PWABUILDER

VIKTIGT: Detta ZIP-paket är färdigt att ladda upp till roten av GitHub-projektet Bilspel.

Gör så här:
1. Packa upp ZIP-filen.
2. Öppna https://github.com/razzlon/Bilspel
3. Ladda upp/ersätt filerna index.html, manifest.json och service-worker.js i projektets huvudmapp.
4. Ladda upp hela mappen icons med alla tre PNG-filer. Mappen ska heta exakt icons.
5. Tryck Commit changes och vänta tills GitHub Pages uppdaterats.
6. Testa sedan denna adress i webbläsaren: https://razzlon.github.io/Bilspel/icons/icon-192.png
   Om ikonen visas och inget 404-fel kommer, testa URL:en https://razzlon.github.io/Bilspel/ i PWABuilder igen.

Förväntad struktur i GitHub:
Bilspel/
  index.html
  manifest.json
  service-worker.js
  icons/icon-192.png
  icons/icon-512.png
  icons/icon-maskable-512.png

Obs: ZIP-filen ändrar inte automatiskt GitHub. Filerna måste laddas upp till repot och sparas (Commit changes) för att de publika webbadresserna ska sluta ge 404.
