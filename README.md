# Shi Shen Online Temple

An interactive 3D web experience for learning how Malaysian Chinese worship 10 popular deities, step by step. You wash your hands, enter through the Dragon Door, lay out offerings, light incense, say your prayer, throw divination blocks, draw a fortune stick, burn gold paper, and leave through the Tiger Door. Every deity has its own temple, offerings, taboos and rituals, and when you make a mistake, the app explains why.

**▶ Play online:** https://hsheng0614.github.io/Prayer-SOP/

---

## The ten deities

| Deity | Temple | Special ritual |
|---|---|---|
| Guan Yin (Goddess of Mercy) | Guan Yin Hall | Chant her name or the Heart Sutra; learn about the "borrowing from the treasury" custom |
| Tua Pek Kong (Earth God) | Hock Teik Temple | "Fire watching" fortune reading, a Penang New Year custom |
| Guan Di (Lord Guan) | Guan Di Temple | Touch the sacred halberd; pledge to keep your word when you pray |
| Mazu (Goddess of the Sea) | Thean Hou Temple | Report your travel plans and receive a safe-journey charm |
| Nine Emperor Gods | Nine Emperor Gods Temple | Wear white, keep the vegetarian fast, light the nine lamps (represented by a tablet and incense urn, as in many local temples) |
| God of Wealth | God of Wealth Hall | Check the almanac and face today's wealth direction |
| Monkey God (Sun Wukong) | Monkey God Temple | Offer him a peach |
| Nezha | Nezha Temple | Pray on behalf of a child and offer a small toy |
| Datuk Gong | Roadside shrine | Yellow candles and yellow cloth, a greeting in Malay; never pork or alcohol |
| Ji Gong (the Mad Monk) | Ji Gong Altar | Offer him wine and he raises his gourd in return |

## Features

- **Full worship sequence**: 6 to 15 steps per deity in traditional order, with the full step list (SOP) always available from the top-right menu.
- **Taboos you learn by doing**: every step includes common mistakes, such as an even number of incense sticks, blowing out the flame, plastic flowers, leftover food, or offering pork to Datuk Gong. A wrong choice costs you "sincerity points" and explains why, and the end-of-visit summary lists every taboo you learned.
- **A distinct temple for each deity**: each has its own colour scheme, murals, decorations and banners.
- **3D statues and offerings**: everything is generated in code, and every offering and item has a picture.
- **Divination blocks and fortune sticks**: the blocks land as a yes, a laughing answer or a no, and any fortune stick you draw must be confirmed with a "yes" throw.
- **Daily wealth direction**: worked out from the day's Heavenly Stem, as in the Chinese almanac (Jia/Yi northeast, Bing/Ding southwest, Wu/Ji north, Geng/Xin east, Ren/Gui south).
- **Vow reminder**: save your wish in the browser and you will be reminded to come back and give thanks when it comes true.

## How to play

1. Open the page, pick a deity, and press Start.
2. Follow the panel at the bottom one step at a time. The button at its top right moves you to the next step.
3. Drag to look around; scroll to zoom.
4. If you get stuck, press "Stuck? Skip this step".

Add a deity code to the end of the URL to open that deity directly: `#guanyin`, `#tpk`, `#guandi`, `#mazu`, `#jiuhuang`, `#caishen`, `#dasheng`, `#nezha`, `#datuk`, `#jigong`.

> The in-app text is in Chinese.

## Running it locally

The whole project is a single `index.html` with the 3D engine bundled inside. Download it and open it in Chrome, Edge or Safari. There is nothing to install.

## Built with

- [three.js](https://threejs.org/) r128 (MIT licence), bundled inside `index.html`
- Plain HTML, CSS and JavaScript, with no framework and no build step
- Fonts: Noto Serif SC and Noto Sans SC from Google Fonts (falls back to system fonts when offline)

## About the content

- The content is compiled from public sources and describes common practice. Malaysian Chinese come from many ancestral backgrounds, and customs differ widely between temples and families, so **local temple practice always takes precedence**.
- Some details could not be fully verified, such as the specific taboos for the Monkey God, Nezha and Ji Gong in Malaysia. The app says so where this applies.
- The fortune-stick poems are original to this project, for entertainment only, and do not come from any real temple.
- Fire watching, treasury borrowing, the safe-journey charm and temple donations are all simulations. No real money is involved.
- Datuk Gong worship draws on Malay culture, and this project presents it respectfully and neutrally.

## Main sources

- [Tua Pek Kong – Wikipedia](https://en.wikipedia.org/wiki/Tua_Pek_Kong)
- [Na Tuk Kong – Wikipedia](https://en.wikipedia.org/wiki/Na_Tuk_Kong)
- [The Nine Emperor Gods Festival – Roots.gov.sg](https://www.roots.gov.sg/ich-landing/ich/the-nine-emperor-gods-festival)
- [Nine Emperor Gods Festival – Wikipedia](https://en.wikipedia.org/wiki/Nine_Emperor_Gods_Festival)
- [Kuala Lumpur Guan Di Temple – Wikipedia](https://en.wikipedia.org/wiki/Kuala_Lumpur_Guan_Di_Temple)
- [Thean Hou Temple – Wikipedia](https://en.wikipedia.org/wiki/Thean_Hou_Temple)
- [Birthday of the Monkey God – Wikipedia](https://en.wikipedia.org/wiki/Birthday_of_the_Monkey_God)
- [Jiaobei (divination blocks) – Wikipedia](https://en.wikipedia.org/wiki/Jiaobei)
- [Daily Chinese Almanac (Tong Shu) – Skillon](https://www.skillon.com/almanac.cfm/date/2026-11-05)

---

Generated with Claude AI — please review before distribution.
