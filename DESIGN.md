---
name: Castillo Viejo
description: Café, pizzas y música bajo una bóveda de ladrillo; the page is the room at night, ceiling first, then the wall.
colors:
  noche: "#140d0a"
  muro: "#1d1410"
  madera: "#3a2416"
  hierro: "#0c0908"
  vacio: "#120c09"
  ladrillo: "#b5532f"
  ladrillo-sombra: "#170804"
  oculo: "#1f3a66"
  oculo-borde: "#0d1a33"
  foco: "#ffb54a"
  foco-hover: "#ffc56e"
  foco-nucleo: "#fff1c9"
  foco-apagado: "#8a6a48"
  hiedra: "#5f8a4a"
  cal: "#ece4d6"
  cal-hover: "#fff7ea"
  texto: "#f4ece2"
  texto-2: "#cbbba8"
  tinta: "#24170f"
  tinta-2: "#5a4636"
typography:
  display:
    fontFamily: "Grenze Gotisch, Iowan Old Style, Georgia, serif"
    fontSize: "clamp(3.4rem, 2.2rem + 6vw, 7rem)"
    fontWeight: 800
    lineHeight: 0.95
    letterSpacing: "0.005em"
  headline:
    fontFamily: "Grenze Gotisch, Iowan Old Style, Georgia, serif"
    fontSize: "clamp(2.4rem, 1.6rem + 3.6vw, 4.4rem)"
    fontWeight: 700
    lineHeight: 0.95
    letterSpacing: "0.005em"
  title:
    fontFamily: "Grenze Gotisch, Iowan Old Style, Georgia, serif"
    fontSize: "clamp(1.7rem, 1.35rem + 1.6vw, 2.6rem)"
    fontWeight: 700
    lineHeight: 0.95
    letterSpacing: "0.005em"
  lead:
    fontFamily: "Hanken Grotesk, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(1.18rem, 1.08rem + 0.5vw, 1.45rem)"
    fontWeight: 400
    lineHeight: 1.45
  body:
    fontFamily: "Hanken Grotesk, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(1rem, 0.96rem + 0.2vw, 1.12rem)"
    fontWeight: 400
    lineHeight: 1.6
  button:
    fontFamily: "Hanken Grotesk, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(1rem, 0.96rem + 0.2vw, 1.12rem)"
    fontWeight: 700
    letterSpacing: "0.03em"
  label:
    fontFamily: "Hanken Grotesk, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(0.84rem, 0.8rem + 0.15vw, 0.92rem)"
    fontWeight: 700
    letterSpacing: "0.08em"
  small:
    fontFamily: "Hanken Grotesk, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(0.84rem, 0.8rem + 0.15vw, 0.92rem)"
    fontWeight: 400
    lineHeight: 1.4
rounded:
  none: "0"
  arch-crown: "32px"
  arch-foot: "6px"
  focus: "4px"
  pill: "999px"
spacing:
  gutter: "clamp(16px, 4vw, 56px)"
  frame-wood: "10px"
  frame-mat: "clamp(10px, 1.6vw, 18px)"
  stack: "clamp(20px, 3vw, 32px)"
  frame-row: "clamp(48px, 5vw, 64px)"
  column: "clamp(40px, 6vw, 88px)"
  vault-foot: "clamp(64px, 9vw, 120px)"
  wall-foot: "clamp(72px, 10vw, 128px)"
components:
  button-arch-amber:
    backgroundColor: "{colors.foco}"
    textColor: "{colors.tinta}"
    typography: "{typography.button}"
    padding: "18px 30px 14px"
    height: "58px"
  button-arch-amber-hover:
    backgroundColor: "{colors.foco-hover}"
  button-arch-plaster:
    backgroundColor: "{colors.cal}"
    textColor: "{colors.tinta}"
    typography: "{typography.button}"
    padding: "18px 30px 14px"
    height: "58px"
  button-arch-plaster-hover:
    backgroundColor: "{colors.cal-hover}"
  status-pill:
    backgroundColor: "{colors.hierro}"
    textColor: "{colors.texto}"
    typography: "{typography.small}"
    rounded: "{rounded.pill}"
    padding: "10px 18px 10px 14px"
  copy-chip:
    textColor: "{colors.texto}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "8px 14px"
  frame:
    backgroundColor: "{colors.madera}"
    rounded: "{rounded.none}"
    padding: "{spacing.frame-wood}"
  frame-mat:
    backgroundColor: "{colors.cal}"
    textColor: "{colors.tinta-2}"
    padding: "{spacing.frame-mat}"
  frame-opening-empty:
    backgroundColor: "{colors.vacio}"
    textColor: "{colors.texto-2}"
    typography: "{typography.small}"
  hours-row:
    textColor: "{colors.texto}"
    typography: "{typography.body}"
    padding: "14px 16px"
---

# Design System: Castillo Viejo

## Overview

**Creative North Star: "The Room at Night"**

The page is the inside of the café after dark, read top to bottom the way a visitor reads the room: first the ceiling, then the wall. The ceiling is a brick dome drawn live on canvas, square courses converging on a night-blue oculus, with a wrought-iron chandelier hanging from it on a chain. The wall below is a run of dark sections, each topped by its own garland of bulbs in ivy, with picture frames hung beneath. Darkness is the ground; light exists only where a bulb, a candle or the oculus puts it, and everything outside that falloff stays dark.

The world is built from the room's own materials: smoked-wood night, fired-red brick, wrought-iron black, bulb amber, ivy green, dark wood frames and lime-plaster mats. The type pairs a Gothic-cut display face (the old castle in the name) with a plain grotesque for everything that has to be read fast on a phone at night. Density is low and generous: a few large statements, frames with room around them, and practical information set plainly.

This world replaces v1 completely. It rejects the papel picado fiesta street and the cream-and-serif rustic café: no cut-paper bunting, no bright sky ground, no light parchment pages.

**Key Characteristics:**
- Dark ground everywhere; the only luminous colour is bulb amber, with real falloff.
- Generated, not photographed, architecture: canvas brick vault, SVG chandelier, SVG garlands.
- Hung frames with plaster mats lit from above; missing real photos are dark unlit openings, not stand-ins.
- Arch-topped action buttons echo the brick arches of the room.
- Motion is physical: a spring-driven chandelier sway, candle flicker, bulbs switching on one by one.

## Colors

A night palette of smoked wood and fired brick, with one warm light colour and one green that only grows on the wire.

### Primary
- **Bulb Amber** (foco): the light of the room. Used for the chandelier and garland glow, the primary arch button (Llamar, Preguntar fechas), focus rings, text selection, the lit status dot when the café is open, and today's row in the hours list. Lit bulb cores burn at **Filament Cream** (foco-nucleo); unlit cores sit at **Cold Filament** (foco-apagado). Hover on the amber button warms to **Bright Amber** (foco-hover).

### Secondary
- **Fired Brick** (ladrillo): the vault. Lives in the canvas dome only, as one of seven fired reds drawn per brick (#9b4023, #b5532f, #8a3a1f, #c2653b, #a84a2a, #7a3219, #b85a33) over the **Mortar Dark** bed (ladrillo-sombra). Never used for text, buttons or section grounds.
- **Night Oculus** (oculo, rimmed in oculo-borde): the single cool colour, a radial night-blue disc at the crown of the dome with four pinprick stars. One per page.

### Tertiary
- **Ivy** (hiedra): garland leaves only, drawn in four greens (#5f8a4a, #4a7339, #6f9b55, #3d6230) at random rotation and scale along each wire.

### Neutral
- **Smoked Night** (noche): page ground, vault falloff, footer-to-vault transition, scrollbar track.
- **Wall Dark** (muro): every wall section's ground, warmed at the top by a soft amber wash under its garland.
- **Wrought Iron** (hierro): chandelier ironwork, the status pill ground (at 78%), and the footer.
- **Frame Wood** (madera): picture-frame moulding and the scrollbar thumb.
- **Unlit Opening** (vacio): the inside of a frame still waiting for a real photo.
- **Lime Plaster** (cal): frame mats and the secondary arch button (Cómo llegar, Abrir ruta); hover lifts to **Fresh Plaster** (cal-hover).
- **Candle Wax** (texto): primary text on dark grounds.
- **Smoke** (texto-2): secondary text, captions on dark, data keys, unknown hours, the unlit status dot.
- **Soot Ink** (tinta) and **Faded Ink** (tinta-2): text on amber and plaster; tinta on buttons and selection, tinta-2 for captions on the mat.
- Hairlines are Candle Wax at 12-14% opacity (lists) and white at 4% (between wall sections).

### Named Rules
**The Earned Light Rule.** Amber means light, action or today, nothing else. It is the glow of a bulb or candle, the fill of a primary action, a focus ring, the open-now dot and today's hours row. If an element is not lit, not tappable and not "today", it does not get amber.

**The Ivy Stays on the Wire Rule.** Green appears only as leaves on the garlands. No green text, buttons, borders or status.

**The One Sky Rule.** The night-blue of the oculus is the only cool colour in the system and appears once, at the crown of the vault.

## Typography

**Display Font:** Grenze Gotisch (with Iowan Old Style, Georgia)
**Body Font:** Hanken Grotesk (with Helvetica Neue, Arial)

**Character:** A Gothic-cut display that carries the "old castle" in the name and section titles, set against a calm, legible grotesque that does all the practical work: offer, hours, address, buttons.

### Hierarchy
- **Display** (800, clamp 3.4rem to 7rem, 0.95): the name in the vault only, with a soft dark text shadow so it reads over the chandelier light.
- **Headline** (700, clamp 2.4rem to 4.4rem, 0.95): wall section titles and the street address.
- **Title** (700, clamp 1.7rem to 2.6rem, 0.95): dish names on the sample menu; at 800 for the rating figure and the footer signature.
- **Lead** (400, clamp 1.18rem to 1.45rem, 1.45): the offer line under the name and each section's opening line, max 34-44ch; phone, Plus Code and coordinates set here at 700 with tabular figures.
- **Body** (400, clamp 1rem to 1.12rem, 1.6): descriptive copy in Smoke, max 60ch.
- **Small** (400, clamp 0.84rem to 0.92rem, 1.35-1.4): captions, notes, status text, empty-frame lines.
- **Label** (700, clamp 0.84rem to 0.92rem, 0.08-0.09em, uppercase): data keys (Teléfono, Plus Code), the "Pregunta" price cell and the credits heading. Labels name a value beside them; they never sit above a heading.

### Named Rules
**The Blackletter Is for Names Rule.** Grenze Gotisch sets names: the café, the sections, the dishes, the address, the signature, the rating number. Sentences, buttons, labels and anything a visitor must read at a glance stay in Hanken Grotesk.

## Layout

One centred column for the vault, then a stack of full-bleed wall sections. Content sits in a 1180px container with a fluid gutter (clamp 16px to 56px). The vault is full width, its canvas filling the header behind the chandelier (clamp 200-340px wide, 250-380px tall) and a centred stack of name, offer, status and actions that overlaps the chandelier's foot slightly.

Each wall section opens with its garland (96px tall, 72px under 860px) running edge to edge, then two-column compositions with unequal fractions (1.05/1, 1/1.2, 1.1/1) and a wide column gap (clamp 40-88px). The house gallery hangs frames on a 12-column grid at staggered spans and offsets (7+5, 5+6, one frame dropped by up to 56px) so the wall reads as hung by hand, not tiled. Frame rows breathe at clamp 48-64px because each frame needs room above it for its hanging wire.

Responsive: under 860px all two-column compositions collapse to one column and the gallery becomes two columns with the wide frames spanning both; under 480px everything is single column and data keys take their own line.

## Elevation & Depth

Depth comes from light and from objects hanging on a wall, not from interface layers. The vault is lit by a screen-blended radial glow centred on the chandelier, then pulled back to dark by a radial falloff to 93% night; a linear gradient fades the vault into the first wall. Each wall carries a soft amber wash (13%) from its garland. Shadows are the shadows of hung, lit objects: they drop downward and are soft and dark.

### Shadow Vocabulary
- **Hung frame** (`box-shadow: 0 18px 30px rgba(0,0,0,0.5), inset 0 0 0 1px rgba(255,255,255,0.06)`): every picture frame; the inset hairline is the bevel of the wood.
- **Arch button** (`box-shadow: 0 10px 22px rgba(0,0,0,0.45)`): primary and secondary arch actions.
- **Unlit opening** (`box-shadow: inset 0 10px 24px rgba(0,0,0,0.7)`): the recess of an empty frame.
- **Name over light** (`text-shadow: 0 4px 18px rgba(0,0,0,0.6)`): the display name in the vault only.
- **Mat light** (`linear-gradient(to bottom, rgba(255,196,120,0.12), transparent 35%, rgba(20,13,10,0.28))`): plaster mats are lit warm from the top edge and darken toward the bottom.

### Named Rules
**The Lit From Above Rule.** Every light source in the room is overhead: chandelier, oculus, garlands. Glows sit on top, mats warm at their top edge, shadows fall downward. Never light a surface from below or from the side.

## Shapes

The room's geometry is square courses and arches. Brick courses are concentric squares rotated 45 degrees, growing taller toward the viewer (4px plus about 2.1px per course) with half-brick offsets on alternate courses, cut by four ribs where the faces meet; the rib falling toward the title fades out before it reaches the name. Frames are hard-cornered rectangles (0 radius) hung from a nail on a two-line wire. Actions are arches: a 32px crown over 6px feet. Pills (999px) are reserved for the status line and small utility chips. Focus rings round to 4px.

### Named Rules
**The Arch Rule.** An action you tap is shaped like an arch (32px crown, 6px foot). Pills are for status and small utilities, rectangles are for frames. Do not swap them.

## Components

### Buttons
Arch-topped, tactile, warm.
- **Shape:** arch, rounded crown and nearly square foot (32px 32px 6px 6px), min height 58px, with a 20px stroked line icon before the label.
- **Primary (amber):** Bulb Amber fill, Soot Ink text, 700 weight with 0.03em tracking, padding 18px 30px 14px (heavier top to sit the label under the crown). Used for calling.
- **Secondary (plaster):** Lime Plaster fill, same ink and geometry. Used for directions.
- **Hover / Focus:** lifts 3px with a long ease (0.4s, cubic-bezier(0.16, 1, 0.3, 1)) and brightens its fill; returns to rest on press; 3px amber focus ring offset 3px.
- **Copy chip:** transparent pill with a 1px Candle Wax hairline at 50%, label type; hover turns border and text amber. Its text swaps to Copiado or Seleccionado for 1.8s.

### Chips
- **Status pill:** Wrought Iron at 78% with a faint amber hairline, small text, a 10px dot that is Smoke when closed and Bulb Amber when open now. Text is computed from Durango time and only ever states the confirmed Friday hour.

### Cards / Containers
- **Picture frame:** Frame Wood moulding (10px) around a Lime Plaster mat (clamp 10-18px), with the mat light gradient, the hung-frame shadow and a hanging wire and nail above the top edge. Photo aspect ratio is set per frame (4/3, 4/5, 1/1, 3/2). Caption sits on the mat in Faded Ink, small type.
- **Unlit opening:** a frame whose photo does not exist yet. Inside the mat it is a recessed Unlit Opening panel at the frame's ratio, with one Smoke line saying what belongs there (Aquí va...) and the caption "Pronto: foto del Castillo Viejo." Stand-in photos that are not of the café say "Foto de referencia." in their caption.
- **Photo swap:** each frame that can hold a real photo carries a key; dropping a file in assets/local/ and naming it in FOTOS_DEL_LOCAL replaces the mat contents with that photo and the caption "Foto del Castillo Viejo." once it loads.

### Lists
- **Sample menu:** ruled rows (14% Candle Wax hairlines), dish name in Title, "Pregunta" label in place of a price, description in Smoke below. Introduced by a small notice with a stroked info icon stating that it is a sample.
- **Hours:** ruled rows with tabular figures; unknown days read "Llama para confirmar" in Smoke, the confirmed day in Candle Wax 700; today's row takes a 14% amber wash and an amber "· hoy" suffix.

### Chandelier (signature)
An SVG wrought-iron ring chandelier in Wrought Iron: dashed chain from the oculus, four arms to a tilted ring, scroll brackets and a finial. Seven wax candles on the near arc, each with a flame and a radial amber halo whose opacity flickers on two summed sine waves (about 0.71-0.93). The whole lamp sways from its top: a slow idle swing (0.8deg, 2.3s period) plus a scroll impulse capped at 10deg, returned by a damped spring (stiffness 22, damping 3.2) as the impulse decays. Reduced motion: no sway, no flicker.

### Garland (signature)
An SVG wire across the top of every wall section, each with a different sag (0.55, 0.38, 0.62, 0.46 of its height) and bulb phase, so no two walls hang alike. Ivy leaves every 13px; bulbs every 74px (54px under 600px wide), each a 22px amber halo and a 4.2px core on a short drop wire. Bulbs start unlit and switch on one by one at 90ms intervals when the garland is 40% in view. Reduced motion: all bulbs are lit on arrival.

### Brick Vault (signature)
The header canvas: concentric square brick courses over Mortar Dark, the four faces shaded differently (0, 0.38, 0.2, 0.55 darkness), four ribs with the title-side rib fading out, the Night Oculus at the crown, the chandelier glow and the dark falloff. Seeded random, so it draws identically every time; redrawn on resize and after fonts load.

## Do's and Don'ts

### Do:
- **Do** keep every section ground dark (noche or muro) and let light come only from a bulb, candle or the oculus.
- **Do** reserve Bulb Amber for light, actions and today (lit glows, the primary arch button, focus, the open dot, today's hours row).
- **Do** shape tappable actions as arches (32px crown, 6px foot) with a leading 20px stroked icon.
- **Do** hang images in frames: wood moulding, plaster mat lit from above, a wire and nail, a downward shadow.
- **Do** show a missing real photo as a dark unlit opening with one line saying what goes there, and caption stand-ins as "Foto de referencia."
- **Do** give each wall section its own garland with its own sag and let the bulbs switch on one by one; light them all at once under reduced motion.
- **Do** set names in Grenze Gotisch and everything a visitor reads to act in Hanken Grotesk.

### Don't:
- **Don't** bring back the v1 papel picado street: no cut-paper bunting, no sky-blue ground, no fiesta brights.
- **Don't** drift into the cream-and-serif rustic café: no light parchment page grounds; plaster lives only on mats and the secondary button.
- **Don't** use amber for decoration, borders or notices that are neither light, action nor today.
- **Don't** put green anywhere but the garland leaves, or blue anywhere but the oculus.
- **Don't** fill an empty frame with a stock photo that passes for the café, or with a placeholder graphic.
- **Don't** set sentences, buttons or labels in the blackletter, or set uppercase labels above headings.
- **Don't** light anything from below or the side; shadows always fall downward.
