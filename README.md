# BoulesAndBites — Angular SSR website (schoolproject)

Website voor een jeu-de-boules-bar, gebouwd tijdens de opleiding HBO Software Development (Hogeschool Utrecht, 2024). Doel van de opdracht: een bestaande horecawebsite herbouwen als moderne, server-side gerenderde Angular-applicatie met een schone componentstructuur.

## Stack

- Angular 17 met standalone components
- Angular SSR (`@angular/ssr`) op een Express-server voor SEO en snelle first paint
- SCSS, Angular Router, RxJS

## Componenten

`src/app/` bevat o.a. `header`, `navbar`, `home`, `reserveer-block`, `faq`, `contact`, `chatbot` en `footer`; routing loopt via een `layout`-component met child routes (`/` en `/faq`).

## Draaien

```bash
cd BoulesAndBites2024
npm install
npm start                  # dev-server op http://localhost:4200
npm run build && npm run serve:ssr:BoulesAndBites2024   # SSR-build
```

## Werkwijze

Het project is uitgevoerd met Jira voor issue-tracking, feature branches met pull requests en code review, en Bitbucket Pipelines voor CI.
