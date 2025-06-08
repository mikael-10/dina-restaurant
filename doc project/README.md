
# 🍽️ Dina Restaurant Site

Questo è un sito web responsive per un ristorante, sviluppato con HTML, CSS, JavaScript e PHP.  
Include funzionalità come gallerie, form contatti, menu dinamici, e layout responsive con Bootstrap.

---

## 📁 Struttura del progetto

```
restaurant-site/
│
├── index.html               ← Homepage principale
├── header-2.html            ← Variante dell'intestazione (header)
├── about-us.html            ← Pagina “Chi siamo”
├── menu-2-col.html          ← Menu a due colonne
├── team-2-cols.html         ← Pagina Team (2 colonne)
├── reservation.html         ← Prenotazione tavoli
├── contact.html             ← Contatti con form + mappa
│
│── style.css                ← Stile personalizzato del sito
│
│
├── css/                     ← Fogli di stile e librerie
│   ├── bootstrap/           ← Framework CSS responsive
│   ├── fontawesome/         ← Icone vettoriali
│   ├── owl-carousel/        ← Carousel immagini
│   ├── magnific-popup/      ← Lightbox popup immagini
│   ├── datepicker.css       ← Stile per selettore data
│              
│
├── js/                      ← JavaScript e plugin
│   ├── jquery.js            ← Libreria base jQuery
│   ├── bootstrap.min.js     ← JS Bootstrap per menu/mobile
│   ├── init.js              ← Script personalizzati
│   ├── contactform.js       ← Validazione form contatti
│   └── altri plugin (datepicker, easing, owl-carousel, ecc.)
│
├── images/                  ← Immagini del sito (slider, piatti, foto team, ecc.)
├── images/icons/            ← Icone PNG del sito (favicon, simboli, ecc.)
├── fonts/                   ← Font e icone web (es. FontAwesome .eot/.woff)
├── include/                 ← Script PHP per gestire i form
│   ├── contact-process.php
│   └── reservation-process.php
```

---

## ✅ Funzionalità

- Layout responsive
- Sezioni parallax
- Gallerie con popup
- Form contatti e prenotazione funzionanti (PHP)
- Icone integrate con FontAwesome
- Slider e animazioni

---

## 📌 Note per lo sviluppatore

- Verifica che il server supporti PHP per far funzionare i form.
- Le immagini di anteprima sono posizionate in `images/` e `images/icons/`.
- Il file `style.css` contiene le regole personalizzate principali.
- Puoi testare tutto localmente con un server come XAMPP o Live Server di VS Code.

---

## ℹ️ Autore del Template

- Template fornito da: Fabio Lombardo. 
- Modificato e studiato da: Mikael Mbiada.
Email: mbiadamikael@gmail.com