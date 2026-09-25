# GMExtractions — Android

Versione Android di **GMExtractions**, software per estrarre attività commerciali (bar, ristoranti, alberghi) da comuni italiani tramite le API di **Geoapify**.

![Platform](https://img.shields.io/badge/Platform-Android-green)
![Qt](https://img.shields.io/badge/Qt-6.11.2-blue)
![Version](https://img.shields.io/badge/Version-1.0.0--beta-orange)

---

## 📱 Cos'è

GMExtractions interroga le API Geoapify per estrarre attività commerciali da un'area geografica (comune, provincia o regione) filtrate per categoria. I risultati sono salvati in un database SQLite locale e visualizzati in una tabella con la possibilità di:

- Marcare ogni attività come **Da visitare / Visitato / Scartato**
- Aggiungere **note personali** e **data di visita**
- Arricchire i dati scaricando il sito web per cercare **email, Instagram, Facebook**
- Aprire la posizione su **Google Maps**
- **Esportare** i risultati in Excel, PDF o CSV

---

## ✨ Funzionalità

| Funzione | Descrizione |
|---|---|
| Ricerca per comune | Estrae attività da un singolo comune |
| Ricerca per provincia | Estrae attività da tutti i comuni di una provincia |
| Ricerca per regione | Estrae attività da tutti i comuni di una regione |
| 56 categorie | Bar, ristoranti, alberghi, negozi, farmacie, ecc. |
| 8126 comuni italiani | Database integrato |
| Stato attività | Da visitare / Visitato / Scartato (con colori) |
| Note personali | Modificabili con doppio tap |
| Arricchimento contatti | Email, Instagram, Facebook dal sito web |
| Esportazione | Excel (.xls), PDF, CSV |
| Google Maps | Apertura posizione con un tap |
| Database SQLite | Storico persistente tra le sessioni |

---

## 📲 Installazione

### Requisiti
- Android 8.0 (API 26) o superiore
- Architettura **arm64-v8a** (tutti i telefoni moderni)

### Download

Scarica l'APK dall'ultima release:
➡️ [**Releases**](../../releases/latest)

Scegli il file corretto:
- `GMExtractions-1.0-beta-arm64.apk` → **telefono Android**
- `GMExtractions-1.0-beta-x86_64.apk` → solo emulatore sul PC

### Installazione
1. Copia l'APK sul telefono
2. Apri il file con il File Manager
3. Consenti "Installa da fonti sconosciute"
4. Installa

---

## 🔑 Ottenere la API Key (gratuita)

1. Vai su [https://www.geoapify.com/](https://www.geoapify.com/)
2. Clicca **Sign up** (nessuna carta di credito)
3. Conferma l'email
4. Vai su [https://myprojects.geoapify.com/](https://myprojects.geoapify.com/)
5. Crea un progetto, copia la chiave dalla sezione **API Keys**

**Piano gratuito**: 3.000 richieste al giorno.

### Inserire la API Key
1. Apri l'app
2. Tocca **⚙ API Key** in alto a destra
3. Incolla la chiave, tocca **OK**

---

## 🚀 Come si usa

1. **Aggiungi comuni** — digita le prime lettere e tocca il suggerimento
2. **Seleziona categorie** — stessa procedura
3. **Scegli modalità** — Comune / Provincia / Regione
4. Tocca **AVVIA RICERCA**
5. Ogni comune ha la sua scheda in alto
6. Tocca **Raggruppa per Via** per organizzare le visite
7. Esporta in **Excel**, **PDF** o **CSV**

I file esportati vengono salvati nella cartella **Download** del telefono.

---

## ⚠️ Limiti

- Fonte dati: **Geoapify** (OpenStreetMap + altre fonti aperte)
- Rating, recensioni e orari **non disponibili** (solo Google Places li fornisce)
- Copertura in Italia: buona ma non completa
- UI in stile desktop (Qt Widgets), non ottimizzata per il touch

---

## 📄 Licenza e crediti

- Framework: Qt 6.11.2 (Open Source, LGPL)
- API: [Geoapify](https://www.geoapify.com/)
- Dati: © OpenStreetMap contributors (ODbL)

© 2026 Massimo Sassano
