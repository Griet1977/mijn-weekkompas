# Mijn Weekkompas V1

Statische huishoudplanner voor GitHub Pages. Alle persoonlijke gegevens blijven in de lokale browseropslag.

## V1
- Takenbibliotheek met frequentie, tijd, prioriteit, weektype en laatste uitvoering
- Kinderweek/kindvrije week, optioneel automatisch afwisselend
- Dagcapaciteit in minuten
- Automatische weekplanning op basis van vervaldatum, prioriteit en beschikbare tijd
- Dagoverzicht, afronden, heropenen en doorschuiven
- Historiek
- JSON back-up/import
- Installeerbare PWA en offline cache

## Publiceren via GitHub Pages
1. Maak op GitHub een nieuwe repository, bijvoorbeeld `mijn-weekkompas`.
2. Pak de ZIP uit. Upload de **inhoud** van de map, zodat `index.html` in de hoofdmap van de repository staat.
3. Commit de bestanden naar `main`.
4. Open **Settings > Pages**.
5. Kies bij **Build and deployment**: **Deploy from a branch**.
6. Kies branch **main**, map **/(root)** en klik **Save**.
7. Open de URL die GitHub bij Pages toont.

## Updaten
Vervang de gewijzigde bestanden in dezelfde repository en commit naar `main`. De site wordt opnieuw gepubliceerd. Exporteer vóór grote updates in de app een back-up.

## Privacy
GitHub Pages is publiek. Zet geen persoonlijke data in de bronbestanden. Ingevoerde taken en planning worden niet naar GitHub gestuurd, maar lokaal in de browser opgeslagen. Een andere browser of toestel heeft dus een aparte gegevensset. Gebruik export/import om over te zetten.
