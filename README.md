# 📁 Gestione Fatture Cantieri - Gama Service

Sistema web per gestire le fatture dei cantieri. Crea cantieri, aggiungi fornitori, scatta foto delle fatture dal cellulare e salvale come PDF su Firebase Storage.

## 🚀 Come usare

1. Apri l'URL dell'app dal cellulare
2. Premi **+** per creare un cantiere
3. Entra nel cantiere, premi **+** per aggiungere un fornitore
4. Entra nel fornitore, premi **+** → si apre la fotocamera
5. Scatta una o più foto → premi "Salva come PDF"
6. Il PDF viene caricato automaticamente su Firebase Storage

## 📱 Installazione come app sul telefono

### iPhone (Safari)
1. Apri l'app in Safari
2. Premi il pulsante condividi (icona quadrato con freccia)
3. Scorri e premi **"Aggiungi a Home"**

### Android (Chrome)
1. Apri l'app in Chrome
2. Menu ⋮ in alto a destra
3. **"Aggiungi a schermata Home"** o **"Installa app"**

## 🗂️ Struttura file su Firebase Storage

```
fatture/
  └── {idCantiere}/
       └── {idFornitore}/
            └── YYYYMMDD_HHMMSS.pdf
```

## 🔧 Stack tecnologico

- **Frontend**: HTML/CSS/JS vanilla (zero dipendenze npm)
- **Database**: Firebase Firestore (cantieri + fornitori)
- **Storage**: Firebase Storage (PDF fatture)
- **PDF**: jsPDF (CDN)
- **Hosting**: GitHub Pages

## 📦 Deploy

Il sito è ospitato su GitHub Pages. Per aggiornarlo basta modificare i file e fare commit — GitHub Pages si aggiorna in automatico in 1-2 minuti.
