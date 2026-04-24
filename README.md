# Olindo Vitale — Sito Personale

Sito web statico single-page per Olindo Vitale, Consulente Sistemi di Gestione.

## Struttura

```
olindo-vitale-site/
├── index.html       # Pagina principale
├── css/
│   └── style.css    # Stili e identità visiva
├── images/          # Immagini (foto profilo, ecc.)
└── README.md
```

## Utilizzo

Apri `index.html` direttamente nel browser, oppure avvia un server locale:

```bash
python3 -m http.server 8080
```

Poi vai su http://localhost:8080

## Tecnologie

- HTML5 puro
- CSS custom (glassmorphism, Google Fonts)
- JavaScript vanilla (IntersectionObserver per animazioni)
- Nessuna dipendenza npm
