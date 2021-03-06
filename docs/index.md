# GitHub Pages eksempel

## Med markdown

**Last ned et markdown redigeringsprogram som f.eks. [Marktext](https://github.com/marktext/marktext) eller [Yank Note](https://github.com/purocean/yn)**

_Brukelige innstillinger og funksjoner_
- _[marktext.md](marktext.md)_
- _[yanknote.md](yanknote.md)_

**Lag en mappe med med innholdet under**

```
.
├─ docs/
|  ├─ images/
|  ├─ _config.yml
|  └─ index.md
|
└─ README.md
```

**Åpne `index.md` i redigeringsprogrammet og fyll den med innholdet du skal ha.**

_Brukelig ressurs til markdown skriving --> [Markdown Cheat Sheet](https://www.markdownguide.org/cheat-sheet/)_

![](images\2022-05-09-11-01-02-image.png)

**Åpne `_config.yml` i et tekstredigeringsprogram som f.eks [Visual Studio Code](https://code.visualstudio.com/) og legg i hva du skal ha som f.eks tittel, beskrivelse og tema**

![](images\2022-05-09-11-17-01-image.png)

## Med HTML

**Lag en vanlig side med html, css osv. Du kan f.eks. bruke [Visual Studio Code](https://code.visualstudio.com/) eller [Adobe Dreamweaver](https://www.adobe.com/no/products/dreamweaver.html).**
_Husk å bruk index.html_

## Sette siden på GitHub Pages

**Gå inn på GitHub og lag et nytt repository**

*Hvis du skriver inn f.eks test_side blir url-en `https://<brukernavn>.github.io/test_side`*

*Det er også mulig å skrive inn f.eks url-en over*

*Må bruke Public hvis man ikke har GitHub Pro*

![](images\2022-05-09-11-23-37-image.png)

**Last mappen opp til GitHub repositorien**

![](images\2022-05-09-11-35-05-image.png)

**Gå inn på innstillinger (Settings) og trykk Pages**

![](images\2022-05-09-11-36-39-image.png)

**Velg source og trykk Save**

![](images\2022-05-09-11-37-17-image.png)

**Trykk Choose a theme**

![](images\2022-05-09-11-37-47-image.png)

**Velg hvilke tema du vil ha og trykk Select theme**

![](images\2022-05-09-11-39-00-image.png)

**Du kan koble til et domenet hvis du har et**

![](images\2022-05-09-11-40-32-image.png)

**Legg url-en inn i README.md** *ikke nødvendig men lettere å gå inn på siden*

![](images\2022-05-09-11-41-26-image.png)

**Gå inn på siden** _Må kanskje vente et par minutter_

![](images\2022-05-09-11-42-46-image.png)

## Redigere tema

**Når du skal redigere temaet burde du først åpne GitHub siden til temaet (eller hvor det ligger)**

![Img](./images/de996f32.png)
_[Leap Day](https://github.com/mattgraham/leapday)_

**Lag en mappe med samme navn som der det du vil redigere ligger**

![Img](./images/a7975899.png)

**Hvis du f.eks. vil endre en farge, skule noe eller sette inn et bakgrunnsbilde, Kan du lage en under mappe som heter `css` og legge til f.eks. `style.scss`** (skal være scss)

**Start `<filnavn>.scss` med**

```scss
---
---

@import "jekyll-theme-leap-day"; /* Tema navn */
```

**Fortsett filen med hva du vil endre**
_Bruk siden til temaet for å se hvordan html malene er settet opp_
_Anbefaler at du bruker [Firefox](https://www.mozilla.org/nb-NO/firefox/new/) (eller en annen nettleser) for å se endringer uten å måtte vente flere minutter på at GitHub Pages oppdaterer seg._

**Ikke redigert:**
![Img](./images/ffbf1d2b.png)

**Redigert:**
![Img](./images/b3a4a1eb.png)

