# Hologram PWA (Pepper’s Ghost) – balíček

## Co je v balíčku
- index.html
- manifest.webmanifest
- sw.js
- icon-192.png, icon-512.png

## Jak to spustit
### Varianta A: GitHub Pages
1) Vytvoř repozitář a nahraj všechny soubory do kořene.
2) Settings → Pages → Deploy from branch (main / root).
3) Otevři odkaz na mobilu.

### Varianta B: lokálně (kvůli service workeru je potřeba server)
- VS Code: Live Server
- nebo Python: `python -m http.server 8000` (v té složce)
Pak otevři: http://localhost:8000

## Demo video
Pokud chceš tlačítko „Demo“, přidej do stejné složky soubor `demo.mp4`
a v `sw.js` ho přidej do ASSETS (odkomentuj).
