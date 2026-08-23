# Vefforritun 1, 2026: Verkefni 1, HTML sýnilausn

[Sýnilausn á verkefni 1](https://github.com/vefforritun/vef1-2026-v1).

## Prettier og W3C validator

[Prettier](https://prettier.io/) í [vscode](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) er notað til að forma HTML. Það setur „sjálflokandi“ (self-closing)
element þar sem við á, t.d. `<meta />` í stað `<meta>`. [W3C validator](https://validator.w3.org/) mun láta vita að þetta sé óþarfi með skilaboðum eins og:

```
Info: Trailing slash on void elements has no effect and interacts badly with unquoted attribute values.

From line 4, column 5; to line 4, column 28

head>↩    <meta charset="utf-8" />↩    <
```
