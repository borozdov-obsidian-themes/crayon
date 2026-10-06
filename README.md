# Borozdov Crayon

A theme from the Borozdov collection. Two faces — light **Daylight**, a notebook page on
cream paper, and dark **Nightlight**, the same page under a desk lamp. Monospace for
everything, charcoal outlines with hard shadows and one sky-blue crayon for what you press.

![Borozdov Crayon in light mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/crayon/main/screenshots/light.png)

![Borozdov Crayon in dark mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/crayon/main/screenshots/dark.png)

## Principles

- **A terminal that refuses to dress like one.** JetBrains Mono for the page and the
  chrome, tracked slightly open; headlines in capitals.
- **Drawn, not rendered.** Every box — callouts, code, tables, tags, buttons, menus — has
  a 2px charcoal outline, 2px corners and a hard offset shadow with no blur.
- **One crayon for action.** Sky blue fills checked tasks, toggles, the main button and
  the open file; a canary marker highlights. The rest of the crayon box comes out only
  for callouts: coral, peach, marigold, lime, mint, periwinkle, lilac.
- **Cream paper, white cards.** Nothing is pure white except the cards themselves.

## Features

- Light and dark modes, following Settings → Appearance → Base color scheme
- Callouts as crayon boxes: a 2px outline in the type's colour, a hard charcoal shadow
- Tags as little label boxes with their own small shadow
- Code and tables on white cards with a charcoal frame and a hard shadow
- Quiet editing: no focus ring around the note, its title or form fields while you type;
  property names read as labels, not boxed fields
- Text colours meet WCAG contrast on both faces
- The phone layout keeps the same colours and shapes
- No `!important`: every rule can be overridden with a CSS snippet

## Installation

**From the community directory, as a variant:** this theme ships inside **Borozdov
Palette**. Install Borozdov Palette under Settings → Appearance → Themes → Manage, then
the [Style Settings](https://github.com/mgmeyers/obsidian-style-settings) plugin, and
choose **Crayon** under Style Settings → Borozdov Palette → Variant. The variant brings
this theme's palette, type and corners; its own layout, and its embedded font if it has
one, come with the full theme below.

**The full theme, by hand:** download `manifest.json` and `theme.css` from the
[latest release](https://github.com/borozdov-obsidian-themes/crayon/releases/latest) into
`<vault>/.obsidian/themes/Borozdov Crayon/`, then choose Borozdov Crayon under
Settings → Appearance → Themes.

## Font

JetBrains Mono (© 2020 The JetBrains Mono Project Authors) is embedded in `theme.css` as
base64 WOFF2 under the SIL Open Font License 1.1 — see [`fonts/OFL.txt`](fonts/OFL.txt).
Weights 400–600, Latin and Cyrillic.

## License

MIT — see [LICENSE](LICENSE).

---

**По-русски.** Тема из коллекции Borozdov. Два лика: светлый «День» — страница блокнота на
кремовой бумаге, и тёмный «Ночник» — та же страница под настольной лампой. Моноширинный
JetBrains Mono для всего, угольные контуры с жёсткими тенями, карандашные цвета в колаутах и
один небесно-голубой для того, что вы нажимаете. В каталоге тема живёт вариантом Borozdov Palette: установите Borozdov Palette и плагин Style Settings, затем выберите Crayon в Style Settings → Borozdov Palette → Variant. Целиком, со своей вёрсткой, тема ставится вручную из последнего релиза репозитория.
