# [NUME FIRMA] - site firma de constructii Buzau

Landing page pentru o firma de constructii din Buzau. Un singur fisier HTML,
cu CSS si JavaScript inline, plus un folder cu imagini. Fara build, fara dependinte.

## Structura

```
index.html      toata pagina: HTML + CSS + JS
imagini/        pozele folosite in pagina si in galerii
```

## Rulare locala

Deschide `index.html` direct in browser. Nu are nevoie de server.
Important: folderul `imagini/` trebuie sa ramana langa `index.html`,
altfel pozele nu se incarca.

## Sectiuni

Hero - Despre - Servicii - Etapele lucrarii - Lucrari realizate -
Cum lucram - Garantii - Testimoniale - Contact - Footer

## Functionalitati

- Meniu hamburger pe mobil, smooth scroll, link activ in meniu
- Animatie la scroll: casa se construieste pe etape (sectiunea "Etapele lucrarii")
- Galerie cu detalii tehnice la click pe fiecare lucrare realizata
- Formular de cerere oferta, cu validare, care trimite pe WhatsApp
- Butoane fixe de telefon si WhatsApp
- Design responsive, mobile first

## De inlocuit inainte de publicare

| Placeholder | Unde apare |
|---|---|
| `[NUME FIRMA]` | title, header, hero, footer |
| `07XX XXX XXX` | numarul afisat, in header, contact si footer |
| `407XXXXXXXX` | variabila `WHATSAPP` din JS si linkurile `wa.me` |
| `tel:07XXXXXXXX` | toate linkurile de apelare |
| `Str. [Strada] nr. [X]` | contact, footer |
| `oferte@[domeniu].ro` | contact, footer |
| `[XX]`, `[XXX]`, `[XXXX]` | cifre din hero, lucrari si detalii tehnice |
| `CUI [RO00000000]`, `Reg. Com. [J10/000/2000]` | footer |
| Linkuri social | `facebook.com/[pagina]`, `instagram.com/[pagina]` |

Harta Google Maps se insereaza in `div.map` din sectiunea Contact
(Google Maps > Partajare > Incorporare harta).

## Lucrarile din portofoliu

Textele si pozele fiecarei lucrari stau in obiectul `PROIECTE` din JavaScript,
la inceputul scriptului. Fiecare lucrare are titlu, descriere, lista de detalii
tehnice si lista de poze pentru galerie.

Pozele actuale sunt de umplutura, cu licenta CC0. Trebuie inlocuite cu pozele
reale ale firmei inainte ca site-ul sa fie folosit ca site de prezentare.
