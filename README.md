# Mina App-resurser 📱

Här samlar jag länkar till gratis verktyg för att bygga min Android-app.

## 🎨 Ikoner (Gratis)
* **Material Design Icons** (Googles standard): https://fonts.google.com/icons
  * *Bäst för:* Att få appen att se ut som en riktig Android-app.
* **Feather Icons**: https://feathericons.com/
  * *Bäst för:* En ren och enkel stil.
* **Phosphor Icons**: https://phosphoricons.com/

## 🖼️ Bilder & Illustrationer
* **Unsplash**: https://unsplash.com/
  * *Vad:* Gratis foton av hög kvalitet (bra för bakgrunder).
* **unDraw**: https://undraw.co/illustrations
  * *Vad:* Gratis illustrationer där du kan byta färg så de matchar din app.
* **Pexels**: https://www.pexels.com/sv-se/

## 🛠️ Verktyg för App-bygge (No-Code)
* **Thunkable**: https://thunkable.com/
* **Glide**: https://www.glideapps.com/
* **MIT App Inventor**: https://appinventor.mit.edu/

## 🎨 Färgval
* **Coolors**: https://coolors.co/
  * *Hjälp:* Skapar färgpaletter som passar ihop automatiskt.# mina-app-resurser
first try

<img width="1908" height="882" alt="image" src="https://github.com/user-attachments/assets/4289b7b6-edb5-4400-93bc-20cda16b2376" />

# 🥚 Äggräknare med Kattfakta (Thunkable)

Det här är min första app byggd i Thunkable. Appen kombinerar lokal datalagring med externa API-anrop.

## Funktioner
* **Räknare:** En knapp som räknar upp antalet ägg.
* **Persistent lagring:** Använder `stored variable` så att appen minns antalet även om man stänger den.
* **API-integration:** Hämtar slumpmässiga kattfakta från `catfact.ninja` varje gång man klickar.

## Hur koden fungerar
1. **Knappklick:** Triggar händelsen.
2. **Uppdatera URL:** Säkerställer att API-anropet går till rätt adress.
3. **Variabel:** Ökar `antal_agg` med 1.
4. **Visa:** Uppdaterar textrutan med nya antalet.
5. **API Call:** Skickar en GET-förfrågan och hämtar JSON-data.
6. **JSON Parsing:** Extraherar egenskapen `fact` ur svaret och visar den på skärmen.

---
### Min kod:
![Bild på mina block](katt_kod.png)
