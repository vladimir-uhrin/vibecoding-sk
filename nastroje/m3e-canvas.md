# M3E Canvas: z naklikaného rozhrania rovno prompt pre AI

**Overené:** 6. 9. 2026  
**Originál:** [lnkiai/m3e-canvas](https://github.com/lnkiai/m3e-canvas)  
**Živé demo:** [lnkiai.github.io/m3e-canvas](https://lnkiai.github.io/m3e-canvas/)  
**Licencia:** MIT

M3E Canvas je vizuálny editor pre Material 3. Obrazovku poskladáš z tlačidiel, kariet, zoznamov, formulárov a navigácie. Obrazovky môžeš prepojiť a nakoniec z celého návrhu vytvoriť podrobný prompt pre Claude Code, Codex, Cursor alebo Gemini CLI.

## Ako ho použiť

1. Otvor živé demo. Účet ani inštalácia nie sú potrebné.
2. Pridaj telefónnu alebo desktopovú obrazovku.
3. Presuň na ňu komponenty a nastav farby, tvary, text a navigáciu.
4. Otvor záložku **Prompt** a vyber Android alebo Web.
5. Skopíruj brief do svojho AI coding nástroja.

## Čo som overil

Na predvolenej telefónnej obrazovke vygeneroval prompt, ktorý obsahoval:

- rozmery a cieľovú platformu,
- farebnú schému a roly farieb,
- poradie a rozloženie komponentov,
- navigáciu, stavy a očakávané správanie,
- odporúčania pre responzivitu a ukladanie dát.

Takýto brief výrazne znižuje priestor, v ktorom musí AI hádať, čo si mal na mysli. Samotný výsledný kód som zatiaľ neporovnával medzi viacerými agentmi, takže netvrdím, že nástroj automaticky vyrobí hotový kvalitný produkt.

## Kedy dáva zmysel

- máš nápad na aplikáciu, ale nevieš ho presne opísať,
- nechceš začínať vo Figme,
- chceš rovnaké zadanie skúsiť v Claude Code, Codexe aj Cursore,
- potrebuješ rýchly prototyp ešte pred prvým riadkom kódu.

## Limity

- drží sa štýlu Material 3 Expressive,
- plný editor je určený hlavne pre desktop,
- prompt je zatiaľ dostupný v angličtine, japončine, čínštine a kórejčine,
- návrh sa ukladá do localStorage prehliadača,
- voliteľný AI pomocník potrebuje tvoj vlastný API kľúč.

Repo malo pri kontrole približne **4,2 tisíca hviezdičiek**. Zdrojový kód je verejný pod licenciou MIT. Autorom projektu je `lnkiai`; táto stránka je moje slovenské zhrnutie a praktické overenie, nie kópia projektu.
