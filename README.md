# ⚡ Confronto Tariffe Energia

Applicazione web per confrontare tariffe elettriche tra operatori del Mercato Libero e Servizio Tutele Graduali (STG).

## 🚀 Deploy

### GitHub Pages
1. Crea un nuovo repository su GitHub
2. Carica tutti i file (`index.html`, ecc.)
3. Vai in **Settings** → **Pages**
4. In "Source" seleziona **Deploy from a branch**
5. Seleziona branch `main` e cartella `/ (root)`
6. Clicca **Save**
7. Attendi 1-2 minuti, il sito sarà su `https://tuousername.github.io/nome-repo/`

### Netlify
1. Vai su [netlify.com](https://netlify.com) e accedi
2. Trascina la cartella `energia-app` nella dashboard
3. Il sito sarà online in pochi secondi

### Vercel
1. Vai su [vercel.com](https://vercel.com) e accedi
2. Importa il repository GitHub o trascina la cartella
3. Deploy automatico

## 📁 Struttura
```
energia-app/
├── index.html      # Applicazione completa (HTML + CSS + JS)
├── netlify.toml    # Configurazione Netlify
├── .nojekyll       # Disabilita Jekyll su GitHub Pages
└── README.md       # Questo file
```

## ✨ Funzionalità
- Wizard guidato in 4 step
- Database offerte con auto-compilazione prezzi
- Ricerca prezzi online (pulsante 🔍)
- Confronto Mercato Libero vs STG
- Calcolo costi annualizzati
- Design responsive

## 📊 Dati utilizzati
I prezzi delle offerte sono indicativi (dicembre 2025) e potrebbero variare.
Verifica sempre sul sito ufficiale dell'operatore.

## 📝 Licenza
MIT - Usa liberamente per scopi personali o commerciali.
