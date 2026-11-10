# Style-guide – Kaviareň Zrnko

## Zadanie
Podľa `text.txt` vytvor vlastné `index.html` a `assets/css/style.css`.


Musíš použiť:
- [ ] sémantické HTML (`header`, `nav`, `main`, `section`, `article`, `footer`)
- [ ] CSS premenné v `:root` (farby z tabuľky nižšie)
- [ ] Google Fonts cez `@import` (nadpisy: Fraunces, text: Nunito)
- [ ] **flexbox** (aspoň hlavička a navigácia)
- [ ] **grid** (aspoň karty a pätička)
- [ ] mobile first: základné štýly sú pre mobil, ďalej len `@media (min-width: ...)`
- [ ] BEM názvy tried (napr. `hlavicka__logo`)
- [ ] `:hover` na odkazoch a tlačidlách
- [ ] žiadny JavaScript

## Farby

hsl(20, 35%, 9%);         
hsl(19, 30%, 14%);     
hsl(31, 48%, 62%);         
hsl(34, 36%, 91%);           
hsl(20, 24%, 17%);          
hsla(34, 36%, 91%, 0.68)

## Fonty

- Nadpisy a logo: **Fraunces**
- Text: **Nunito**
- Základná veľkosť textu: `1.1rem`, riadkovanie `1.7`

## Breakpointy
| Zariadenie | Šírka | Karty |
|---|---|---|
| Mobil | do 599px (základ) | 1 stĺpec |
| Tablet | od 600px | 2 stĺpce |
| Desktop | od 900px | viď layout nižšie |

Desktop layout karty: 3 stĺpce.

## Odsadenia
- Bočné odsadenie sekcií: `5%` (na desktope môže byť viac)
- Vertikálne odsadenie sekcií: `3rem`
- Medzery medzi prvkami: `1rem` až `2rem`
