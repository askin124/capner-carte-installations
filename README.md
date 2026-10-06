# Carte des installations Capner au Luxembourg

Page statique (GitHub Pages) : un drapeau Capner par localité où une
installation a été réalisée. Aucune donnée nominative : seulement la
localité, la commune et le nombre d'installations.

- `index.html`, `assets/` : la page (Leaflet + Leaflet.markercluster, fond OpenStreetMap).
- `data/installations.json` : données agrégées, générées hors de ce dépôt
  et mises à jour manuellement.

Pour tester en local, servir le dossier avec `python -m http.server 8765`
puis ouvrir http://localhost:8765/ (ouvrir `index.html` directement ne charge
pas les données).
