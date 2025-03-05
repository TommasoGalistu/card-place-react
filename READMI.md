# ⚛️ PlacePicker - React App

Benvenuto in **PlacePicker**, un'applicazione React che consente agli utenti di **ordinare le destinazioni turistiche in base alla loro posizione** e **salvare i luoghi che vorrebbero visitare**. 🚀

## 📥 Clonazione del progetto

Per ottenere una copia locale del progetto, esegui il seguente comando nel tuo terminale:

```bash
    git clone https://github.com/TommasoGalistu/card-place-react.git

🚀 Installazione e Avvio

Dopo aver clonato il repository, segui questi passaggi per avviare il progetto:

Spostati nella cartella del progetto:

    cd card-place-react

Installa le dipendenze necessarie:

    npm install

Avvia l'applicazione in modalità sviluppo:

    npm run dev


🛠️ Funzionalità

✔️ 📍 Geolocalizzazione → Rileva la posizione dell'utente e ordina i luoghi in base alla distanza.
✔️ 📌 Selezione e gestione preferiti → I luoghi selezionati vengono salvati nel localStorage.
✔️ ⚡ Performance ottimizzate → Utilizzo di useCallback e React.memo per evitare re-render inutili.
✔️ 🛑 Modale con progress bar → Conferma per la rimozione dei luoghi con timer visivo.
📌 Struttura del Progetto


🔧 Tecnologie Utilizzate

    ⚛️ React con Hooks (useState, useEffect, useRef, useCallback)
    🗺️ Geolocalizzazione (navigator.geolocation)
    💾 Gestione dello stato locale e localStorage
    🎨 CSS per lo stile dell'interfaccia
    🌐 ES6+ JavaScript

🛠️ Possibili Miglioramenti

🔹 Aggiungere un backend per salvare i preferiti su database
🔹 Implementare una visualizzazione su Google Maps
🔹 Migliorare il design con TailwindCSS o Styled Components