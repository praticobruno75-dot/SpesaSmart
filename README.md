# Smart Shopping List - PWA

App web progressiva per gestire la spesa, confrontare prezzi tra supermercati e risparmiare!

## 📁 File necessari

Per deployare la PWA hai bisogno di questi file:

1. **lista-spesa-v2.html** - File principale dell'app (rinominalo in `index.html`)
2. **manifest.json** - Configurazione PWA
3. **service-worker.js** - Per funzionamento offline
4. **icon-192.png** - Icona 192x192px
5. **icon-512.png** - Icona 512x512px

## 🎨 Come creare le icone

Hai il file `icon.svg` da convertire in PNG:

### Opzione 1: Online (più semplice)
1. Vai su https://cloudconvert.com/svg-to-png
2. Carica `icon.svg`
3. Converti in:
   - PNG 192x192px (salvalo come `icon-192.png`)
   - PNG 512x512px (salvalo come `icon-512.png`)

### Opzione 2: Con software
- Usa Inkscape, GIMP o Photoshop
- Esporta in 192x192 e 512x512 px

## 🚀 Deploy su GitHub Pages

1. **Rinomina il file principale:**
   ```
   lista-spesa-v2.html → index.html
   ```

2. **Carica tutti i file nel repository:**
   ```
   index.html
   manifest.json
   service-worker.js
   icon-192.png
   icon-512.png
   ```

3. **Attiva GitHub Pages:**
   - Settings → Pages
   - Source: main branch, / (root)
   - Save

4. **Aspetta 2-3 minuti**
   L'app sarà disponibile su: `https://tuo-username.github.io/nome-repo/`

## 📱 Come installare la PWA

### Su Android (Chrome):
1. Apri l'app nel browser
2. Menu (⋮) → "Installa app" o "Aggiungi a schermata Home"
3. Conferma

### Su iPhone (Safari):
1. Apri l'app in Safari
2. Tap su "Condividi" 
3. "Aggiungi a Home"
4. Conferma

### Su Desktop (Chrome/Edge):
1. Apri l'app nel browser
2. Icona "⊕" o "+" nella barra degli indirizzi
3. "Installa"

## ✅ Verifica installazione

Dopo l'installazione dovresti vedere:
- ✅ Icona dell'app nella schermata Home
- ✅ App si apre a schermo intero (senza barra del browser)
- ✅ Funziona offline dopo la prima apertura
- ✅ Appare nel drawer delle app

## 🔧 Troubleshooting

**La PWA non si installa:**
- Verifica che il sito sia su HTTPS (GitHub Pages lo è automaticamente)
- Controlla che manifest.json e service-worker.js siano caricati
- Apri Console (F12) e cerca errori

**Le icone non appaiono:**
- Verifica che icon-192.png e icon-512.png siano nella root
- Controlla che i nomi file corrispondano esattamente
- Prova a ricaricare con Ctrl+Shift+R

**Non funziona offline:**
- Apri l'app almeno una volta con connessione
- Il service worker si registra al primo caricamento
- Ricarica la pagina

## 📊 Funzionalità

✅ Scansione codici a barre  
✅ Storico prezzi per supermercato  
✅ Grafici comparativi  
✅ Liste condivisibili via WhatsApp  
✅ Backup e ripristino dati  
✅ Funzionamento offline  
✅ Installabile come app nativa  

## 🆕 Versione

**v2.0** - Con supporto PWA e supermercati

---

**Made with ❤️ for smart shoppers!**
