# Mijn Leefplanner V1

Een statische, mobiele webapp voor GitHub Pages met:

- Dashboard met taakvoortgang, 100%-melding en werkelijk bestede tijd
- Dagelijkse taken in grijs en extra taken in zwart
- Tijd, frequentie, datum, achterstallige aanduiding en automatisch herplannen
- Weekmenu, uitbreidbare gerechtenbibliotheek en aantal eters per dag
- Kindermodus met alleen toegang tot de maaltijdplanner
- Uitgebreide lijst "Soms vergeten"
- Hobby's/sport als bezette tijd in de weekplanning
- JSON export/import

## Publiceren op GitHub Pages

1. Pak het ZIP-bestand uit.
2. Upload `index.html`, `styles.css` en `app.js` naar de hoofdmap van je repository.
3. Ga naar Settings > Pages.
4. Kies bij Branch `main` en map `/(root)`.
5. Klik Save.

## Belangrijk over delen tussen toestellen

Deze versie bewaart gegevens in `localStorage`. Dat betekent:

- gegevens blijven in dezelfde browser op hetzelfde toestel bewaard;
- de kindermodus is een gebruiksbeperking en geen echte beveiligde login;
- wijzigingen synchroniseren niet automatisch tussen verschillende telefoons;
- export/import kan gebruikt worden om gegevens handmatig over te zetten.

Voor echte gelijktijdige gezinsdeling is in een volgende versie een databank en gebruikerslogin nodig, bijvoorbeeld via Firebase of Supabase.

## Standaard oudercode

`1977` (aanpasbaar bij Instellingen)
