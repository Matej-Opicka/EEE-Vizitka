# E-vizitka — finální handoff

## Font
**Space Grotesk** z Google Fonts

Použité řezy:
- 400
- 500
- 600
- 700

## Barvy
- pozadí: `#D8D3C9`
- světlé karty: `#F5F2EA`
- tmavá karta: `#181818`
- zelená karta: `#D8FF45`
- fialová karta: `#6758F5`

## Rozměry
- max. šířka: `1200px`
- mezera mezi kartami: `14px`
- padding: `28px`
- radius: `24px`

## Grid
Desktop:

```css
grid-template-columns: 1.5fr 1.05fr 0.9fr;
grid-template-areas:
  "intro skills project"
  "intro about contact";
```

Levá karta zabírá oba řádky.

## Typografie
- malý popisek: `12px`
- běžný text: `16–17px`
- text v kartách: přibližně `26–58px`
- hlavní jméno: přibližně `74–132px`

## Princip
Nejde o pixel-perfect kopii. Důležité je zachovat:
- výraznou hlavní kartu,
- jasnou hierarchii,
- dostatek prostoru,
- maximálně dvě výrazné akcentní barvy,
- jednoduchou responsivitu.

## Co použít
- HTML
- CSS Grid
- Flexbox
- `gap`
- `padding`
- `border-radius`
- `clamp()`
- `@media`

Bez JavaScriptu a frameworků.
