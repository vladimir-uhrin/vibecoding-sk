# Archify: interaktívna mapa architektúry z repozitára

Archify je otvorený agent skill, ktorý mení popis systému alebo zdrojový kód na interaktívny technický diagram. Funguje s Claude Code, Codex CLI, Cursorom a OpenCode.

## Čo som overil

Na test som zmapoval náš PULSE agent na vyhľadávanie trendov. Diagram obsahuje zdroje GitHub, YouTube a webové komunity, samostatné skenery, hodnotenie trendov, databázu a Telegram.

Výstup prešiel všetkými 9 kontrolami Archify bez chyby a bez varovania. Výsledkom je jeden samostatný HTML súbor. Dá sa v ňom:

- prepínať medzi svetlou a tmavou témou,
- vyhľadávať komponenty,
- sledovať cestu medzi dvoma bodmi,
- zvýrazniť upstream a downstream väzby,
- exportovať PNG, SVG, WebM alebo celý HTML súbor.

### Výstupy nášho testu

- [Pozrieť výsledný diagram](archify/pulse-agent.png)
- [Pozrieť zdrojový JSON diagramu](archify/pulse-agent.architecture.json)

Zdrojový JSON je zámerne verejný. Môžeš si ho stiahnuť, upraviť komponenty a vyrenderovať vlastnú verziu.

## Inštalácia

Potrebuješ Node.js 18 alebo novší.

```bash
npx skills add tt-a1i/archify -g
```

Potom môžeš agentovi napísať napríklad:

```text
Analyzuj tento repozitár a pomocou Archify vytvor mapu jeho runtime architektúry.
Ukáž 8 až 12 hlavných komponentov, hlavnú cestu dát, externé služby
a hranice dôvery. Tvrdenia opieraj o reálne súbory v repozitári.
```

## Kedy sa hodí

- preberáš cudzí alebo starší projekt,
- vysvetľuješ systém kolegovi alebo klientovi,
- pripravuješ technickú dokumentáciu,
- kontroluješ zmenu architektúry pred zlúčením pull requestu,
- potrebuješ ukázať tok dát, API volania alebo životný cyklus procesu.

## Na čo si dať pozor

Archify je renderer a validačný systém, nie detektor pravdy. Ak agent nesprávne pochopí projekt alebo mu dáš neúplný popis, môže vytvoriť presvedčivý, ale nepresný diagram. Pri dôležitom projekte preto žiadaj odkazy na konkrétne súbory a výsledok skontroluj.

Projekt je pod licenciou MIT. Pri teste som vypol jeho voliteľnú kontrolu aktualizácií, takže diagram vznikol lokálne bez odosielania projektu do služby Archify.

## Odkazy

- [Originálny repozitár](https://github.com/tt-a1i/archify)
- [Živá galéria](https://tt-a1i.github.io/archify/gallery.html)
- [Návod k scenárom](https://tt-a1i.github.io/archify/guide.html)
