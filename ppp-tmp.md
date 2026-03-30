1. Generate a reveal.js slide deck (~15 in total)
  - use jsDelivr remote scripts to eliminate need to install
  - theme: presentation of three possible occupations after French SPI (Science pour Ingenieur) licence(bac+3)
  - audience: French speaking SPI students
  - requirements
    - simple, plain, direct, confident style
    - reasonable amount of text content
    - use plantUML diagrams where relevant
      - use `https://img.plantuml.biz/plantuml/png/{64 encode string}` online rendering to minimize install
    - inclusive and succint language
      - where relevant, use gender-inclusive conjugaisons: (e.g., étudiant·e, motivé·e)
  - occupations to present
    - [enseignant·e-chercher·euse](https://www.onisep.fr/ressources/univers-metier/metiers/enseignant-chercheur-enseignante-chercheuse)
    - [professeur·e des écoles](https://www.onisep.fr/ressources/univers-metier/metiers/professeur-des-ecoles-professeure-des-ecoles)
    - Ingénieur·e pédagogique
2. Generate also a `laborpriskribo` for each of the three occupations presented in esperanto in `.enc` format

`.enc` ENCIK Formato: 
```enc
terminologio.{2-letter-lang-code} = "..."
difino.{2-letter-lang-code} ="""
## punkto 1

- abcd
- efg
- hij

## punkto 2

- abcd
- efg
- hij
  - lmn

## punkto 3,4,5,6...

- abc..
  - ...
- efg..
- ...
  - ...
  - ...
"""

fonto = [{titolo="...", autoro="...", jaro=2020, tipo="libroj", noto="...", ligilo="https://..."}].
```

Validaj  tipoj por fonto: libroj, artikoloj, retejoj, filmoj, tezoj, raportoj, podkastoj, prelegoj (aŭ aliasoj: lib, art, ret, fil, tez, rap, pod, pre).
