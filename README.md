# Biddir Mouaad — Studio

Portfolio di Biddir Mouaad, sviluppatore software e web designer: gestionali di magazzino, software operativi e siti web su misura.

## Struttura

Tutto il sito è in un unico file, `index.html` (HTML, CSS e JavaScript inline, nessuna dipendenza né build).

- **Tema chiaro / scuro**: chiaro "tavola tecnica", scuro "terminale". Segue il sistema, con interruttore in alto.
- **Contatti**: modifica l'oggetto `CONTACT` in cima al `<body>` (email e numero WhatsApp).
- **Progetti**: aggiungi i lavori all'array `PROJECTS` nello script in fondo. Finché è vuoto il sito mostra lo stato "in cantiere"; con più tipi di progetto compaiono i filtri.
- **Colori**: tutti i token sono nel blocco `DESIGN TOKENS` in cima al CSS.

## Pubblicazione

Pensato per GitHub Pages: Settings → Pages → Deploy from branch → `main` / root.
