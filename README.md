# Torben Carstensen – Fotografie

Eine einfache Website für GitHub Pages. Sie besteht aus HTML, CSS und JavaScript und braucht keinen Build-Schritt.

## Bilder einfügen

Lege im Repository einen Ordner mit dem Namen `bilder` an. Lade deine Fotos mit genau diesen Dateinamen hoch:

- `titelbild.jpg` – großes Bild oben auf der Startseite
- `natur-01.jpg` – erstes großes Naturbild
- `landschaft-01.jpg` – Landschaft
- `reise-01.jpg` – Reisebild
- `natur-02.jpg` – zweites Naturbild
- `landschaft-02.jpg` – zweite Landschaft
- `reise-02.jpg` – zweites Reisebild
- `ueber-mich.jpg` – Foto von dir oder deiner Kamera

Die Namen müssen exakt gleich geschrieben sein, auch die Dateiendung. Wenn deine Bilder PNG-Dateien sind, ändere in `index.html` die jeweilige Endung von `.jpg` auf `.png`. Wenn du noch keine Fotos parat hast, kannst du den Ordner und die Bilder später hinzufügen. Die leeren Bildbereiche sind dafür bereits vorbereitet.

## Google Drive

Öffne Google Drive, gehe auf den Galerieordner und wähle **Teilen → Link kopieren**. Ersetze in `index.html` beim Abschnitt `id="galerie"` die Adresse `https://drive.google.com/` durch deinen Freigabelink.

Bei „Jeder, der über den Link verfügt“ kann jede Person mit dem Link auf die freigegebenen Inhalte zugreifen. Teile dort nur Bilder, die du so freigeben möchtest. GitHub Pages selbst bietet bei dieser einfachen statischen Website keinen echten Passwortschutz.

## GitHub Pages veröffentlichen

1. Erstelle auf GitHub ein neues Repository, zum Beispiel `torben-fotografie`.
2. Lade `index.html`, `style.css`, `script.js`, `impressum.html` und `README.md` hoch.
3. Lege im Repository den Ordner `bilder` an und lade deine Fotos mit den oben genannten Namen hinein.
4. Öffne **Settings → Pages**.
5. Wähle „Deploy from a branch“, den Branch `main` und den Ordner `/ (root)`, dann speichere.

## Impressum

In `impressum.html` ist deine E-Mail-Adresse bereits eingetragen. Ergänze deine vollständige Anschrift und prüfe vor Veröffentlichung die für deine Website geltenden rechtlichen Anforderungen.
