# Hvordan lage en applikasjon i React/Vue/SvelteKit

## Hva du vil lære
- Hvordan opprette en ny mappe for prosjektet ditt.
- Hvordan installere Node.js og bruke npm for å håndtere pakker.
- Hvordan bruke terminalen for å navigere og sette opp prosjektet ditt.
- Hvordan opprette et nytt prosjekt ved hjelp av Vite og velge rammeverk (React, Vue, SvelteKit).
- Hvordan installere nødvendige avhengigheter og kjøre applikasjonen.
- Hvordan gjøre endringer på prosjektet ditt ved å bruke Visual Studio Code.

---

## Oppstart

### Opprett en mappe for prosjektet
- Åpne **File Explorer**.
- Finn hvor du vil opprette prosjektet.
- Høyreklikk, velg **Ny fil** eller **Ny mappe**, og gi den et navn.

---

### Installer en pakkebehandler (Node.js)
For å bruke `npm` må du først installere **Node.js**, som inkluderer `npm` (Node Package Manager):
1. Gå til [Node.js sin offisielle nettside](https://nodejs.org/).
2. Last ned **LTS-versjonen** (Long Term Support) for stabilitet.
3. Kjør installasjonsfilen og følg instruksjonene.
4. Bekreft installasjonen:
   - Åpne terminalen og skriv:
```
node -v
npm -v
```
   - Du skal se versjonsnumre for både Node.js og npm.

---

### Åpne terminalen og naviger til mappen
- Åpne **Command Prompt** (Windows):
  - Trykk på **Start**, skriv inn "Command Prompt", og åpne programmet.
- Naviger til mappen du nettopp opprettet ved å skrive:
  bash
  cd <sti-til-mappen>
  Eksempel:
  bash
  `cd C:\Users\Pc\React`
- Hvis du får en feilmelding, sett stien i anførselstegn:
  `
  cd "C:\Users\Pc\React"
  `

---

## Oppsett

### Opprett prosjektet med Vite
- Når du er i riktig mappe i terminalen, skriv:
  bash
  `npm create vite@latest`
- Følg instruksjonene:
  - Du vil se:
    ```
    Project name: » vite-project
    ```
    Skriv inn et ønsket navn på prosjektet ditt og trykk **Enter**.
  - Deretter ser du:
    ```
    Package name:
    ```
    Trykk **Enter** for å godta standardverdien.
  - Velg rammeverk:
    - Du får en liste over alternativer som ser slik ut:
      ```
      Select a framework: » - Use arrow-keys. Return to submit.
        Vanilla
        Vue
        React
        Preact
        Lit
        Svelte
        Solid
        Qwik
        Angular
        Others
      ```
    - Bruk piltastene til å navigere og trykk **Enter** for å velge.
  - Avhengig av valget ditt, vil du få flere alternativer:
    - For eksempel, hvis du velger **React**, vil du se:
      ```
      Select a variant: » - Use arrow-keys. Return to submit.
      TypeScript
      TypeScript + SWC
      JavaScript
      JavaScript + SWC
      Remix
      ```

---

## Installering

### Installer prosjektet
- Etter å ha opprettet prosjektet, kopier og lim inn følgende kommandoer i terminalen:
  ```
  cd <prosjektmappe>
  npm install
  npm run dev
  ```

- Når du kjører `npm run dev`, vil terminalen vise noe slikt:
  `Local: http://localhost:3000/`
- Hold inne **Ctrl** og klikk på linken for å åpne applikasjonen i nettleseren.

---

## Endringer

### Rediger prosjektet
- Du kan bruke en kode-editor som **Visual Studio Code (VS Code)** for å redigere prosjektet.
- Åpne prosjektmappen i VS Code:
- Gå til `src`-mappen for å finne de viktigste filene, som:
  - `App.tsx` (React)
  - `App.vue` (Vue)
  - `App.svelte` (Svelte)
- Her kan du legge til eller endre komponenter, CSS-stiler og funksjonalitet.
- Hvis du vil stoppe serveren midlertidig, trykk `Ctrl + C` i terminalen og bekreft med `y`.

---

## Tips
- Ikke bekymre deg for filer i `node_modules`. Dette er avhengigheter som prosjektet bruker, og du trenger vanligvis ikke å endre noe her.
- Lagre ofte, og sjekk nettleseren for å se endringer live.
