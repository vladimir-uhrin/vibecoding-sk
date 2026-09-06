# Vibe coding a AI — po slovensky

Kurátorovaný zoznam nástrojov, agentov a trikov na programovanie s AI.
Claude Code, Cursor, agenti, MCP, prompty. To čo naozaj funguje, nie čo znie dobre v článku.

Robím k tomu skupinu na Facebooku, kde to rozoberáme po slovensky a česky:
**[Vibe coding a AI](https://www.facebook.com/groups/1620719039632356)**

Tento zoznam dopĺňam každý týždeň. Ak ti niečo chýba, hoď issue alebo pull request.

---

## Kde začať (ak si úplný začiatočník)

1. **[ChatGPT](https://chat.openai.com)** alebo **[Claude](https://claude.ai)** v prehliadači — najprv sa zohraj s promptami, zisti čo AI vie a čo nie.
2. **[Cursor](https://cursor.com)** — editor s AI priamo v ňom. Vidíš každú zmenu, schvaľuješ ju ručne. Dobré na učenie.
3. **[Claude Code](https://www.anthropic.com/claude-code)** — AI rovno v termináli, spraví aj viac súborov naraz. Keď už vieš čo chceš.

---

## Nástroje (editory a asistenti)

| Nástroj | Čo to je |
|---|---|
| [Claude Code](https://www.anthropic.com/claude-code) | AI agent v termináli. Zadáš úlohu, maká sám naprieč súbormi. |
| [Cursor](https://cursor.com) | Editor postavený na VS Code s AI zabudovanou dnu. |
| [GitHub Copilot](https://github.com/features/copilot) | Napovedanie kódu priamo v editore. Klasika. |
| [Windsurf](https://windsurf.com) | Ďalší AI editor, konkurencia Cursoru. |
| [Cline](https://github.com/cline/cline) | Open-source AI agent ako rozšírenie do VS Code. |
| [Aider](https://github.com/paul-gauthier/aider) | AI párové programovanie v termináli, funguje s hocijakým modelom. |

---

## MCP (Model Context Protocol)

MCP je štandard, cez ktorý AI vie siahnuť na tvoje nástroje — databázu, súbory, GitHub, Slack. Raz nastavíš, funguje všade. Berte to ako "USB pre AI".

- **[Oficiálne MCP servery](https://github.com/modelcontextprotocol/servers)** — zoznam hotových serverov od tvorcov protokolu.
- **[Awesome MCP Servers](https://github.com/punkpeye/awesome-mcp-servers)** — veľká komunitná zbierka.

---

## Šetrenie tokenov (aby ťa to nestálo majland)

- **[DeepSeek](https://www.deepseek.com)** — lacný model, dá sa napojiť do Claude Code aj Cursoru. Za pár centov to čo inde za doláre.
- Trik: nechaj AI odpovedať stručne a bez omáčky. Menej tokenov = menej peňazí.

---

## Nálezy týždňa (čo práve rastie na GitHube)

Sem hádžem repá, ktoré týždeň čo týždeň vystrelia. Overte si sami, či sa hodia na to čo robíte.

- **[M3E Canvas](nastroje/m3e-canvas.md)** — naklikáš rozhranie v prehliadači a dostaneš z neho podrobný prompt pre Claude Code, Codex, Cursor alebo Gemini CLI. Overené 6. 9. 2026.
- **[Archify](nastroje/archify.md)** — z popisu systému alebo repozitára vytvorí kontrolovanú interaktívnu mapu architektúry. Overené na našom PULSE agentovi 6. 9. 2026.
- **[obra/superpowers](https://github.com/obra/superpowers)** — sada schopností (skills) pre Claude Code.
- **[usestrix/strix](https://github.com/usestrix/strix)** — open-source AI agent na hľadanie dier v bezpečnosti kódu.
- **[JuliusBrussee/caveman](https://github.com/JuliusBrussee/caveman)** — skráti prompty tak, že AI "hovorí ako jaskyniar", a ušetrí tokeny.

---

## Moje veci

Sem pridám vlastné configy, prompty a CLAUDE.md, ktoré reálne používam. (Čoskoro.)

---

*Robí [Vladimír Uhrin](https://www.facebook.com/groups/1620719039632356). Ak ti to pomohlo, hoď ⭐ hore — pomôže to, aby to našli aj ďalší.*
