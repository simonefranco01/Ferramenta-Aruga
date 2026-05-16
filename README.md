# Sito Ferramenta Aruga

Sito web per **Ferramenta Aruga** — Via Graglia 6, 10136 Torino.

📞 011 353934  
📍 Via Graglia 6, 10136 Torino  
⏰ Lun-Ven 9:00-12:30 / 15:30-19:00 · Sab 9:00-12:30

---

## 🚀 Come metterlo online (3 strade, dalla più semplice)

### Opzione 1 — Netlify Drop (la più facile, in 30 secondi)
1. Vai su [app.netlify.com/drop](https://app.netlify.com/drop)
2. Trascina il file `index.html` (o l'intera cartella) nella finestra
3. Pronto! Hai un indirizzo tipo `ferramenta-aruga-xyz.netlify.app`
4. Per collegare un dominio tuo (es. `ferramentaaruga.it`), vai nelle impostazioni del sito su Netlify

### Opzione 2 — GitHub Pages
1. Crea un account su [github.com](https://github.com)
2. Crea un nuovo repository chiamato `ferramenta-aruga` (o come preferisci)
3. Carica tutti i file di questa cartella nel repository
4. Vai in **Settings → Pages**
5. Imposta **Source: Deploy from branch** → `main` → `/ (root)`
6. Aspetta 1-2 minuti, il sito sarà online su `https://TUONOMEUTENTE.github.io/ferramenta-aruga/`

### Opzione 3 — Hosting tradizionale (Aruba, SiteGround, ecc.)
1. Compra un hosting + dominio (es. su [aruba.it](https://aruba.it), ~30€/anno)
2. Apri il pannello di controllo del tuo hosting
3. Carica tutti i file di questa cartella nella cartella `public_html` (o `www`) via FTP
4. Il sito sarà visibile sul tuo dominio

---

## 📁 Cosa c'è dentro

```
ferramenta-aruga/
├── index.html              ← il sito (apri questo per vedere)
├── assets/                 ← logo e immagini
│   ├── logo-aruga.jpeg
│   ├── logo-aruga.png
│   └── logo-aruga-crop.png
├── components/             ← il codice del sito (in pezzi)
│   ├── data.jsx            ← dati: recensioni, prodotti, contatti
│   ├── icons.jsx           ← icone SVG
│   ├── dir-c-part1.jsx     ← header, hero, reparti
│   └── dir-c-part2.jsx     ← storia, shop, recensioni, mappa, footer
└── README.md               ← questo file
```

---

## ✏️ Come modificare il sito

### Cambiare testi, recensioni, prodotti
Apri `components/data.jsx` con un editor di testo (consigliato: [VS Code](https://code.visualstudio.com), gratis). Trovi:
- **CONTATTI** — telefono, indirizzo, orari
- **SERVIZI** — gli 11 reparti
- **RECENSIONI** — le recensioni dei clienti
- **PRODOTTI** — i prodotti dello shop (nome, prezzo, categoria, emoji)

Modifica, salva, ricarica la pagina del browser.

### Cambiare il logo
Sostituisci i file in `assets/` mantenendo gli stessi nomi.

### Cambiare colori e layout
Modifica `components/dir-c-part1.jsx` (palette `C` all'inizio del file: giallo, blu, rosso).

---

## 🛠 Versione "tutto in un file"
Se ti serve un **singolo file HTML** che funziona offline e ovunque senza altre cartelle, usa `Ferramenta Aruga - standalone.html` (incluso nello zip se l'hai scaricato). Quello è autocontenuto: lo carichi e basta, senza la cartella `components/`.

---

## ❓ Domande frequenti

**Posso vendere online davvero da questo sito?**  
No — il carrello è solo una vetrina. Per vendere davvero ti serve Shopify, WooCommerce o simili. Questo sito è una **vetrina informativa** (la gente ti trova, vede cosa offri, ti chiama o viene in negozio).

**Posso aggiungere altre pagine?**  
Sì, ma serve un po' di codice. Scrivimi e ti aiuto.

**Il sito è ottimizzato per smartphone?**  
Sì, si adatta a telefoni e tablet.

---

*Sito creato nel 2026 · Per Ferramenta Aruga, dal 1986 a Torino.*
