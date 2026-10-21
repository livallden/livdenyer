---
name: Liv Allden
description: A personal CV read as a slow drive down a country lane, from now back to the start.
colors:
  sky: "#e5eef0"
  sky-deep: "#9fc2cc"
  meadow: "#e3ebdd"
  hill-1: "#d0e0cc"
  hill-2: "#b5cfae"
  hill-3: "#97b991"
  hedge: "#5a8664"
  lane: "#ece9dc"
  ink: "#213429"
  ink-soft: "#4a5d50"
  betty: "#3e8a5c"
  betty-deep: "#2f6e48"
  snow: "#fbfcfa"
  glass: "#cfe2e6"
  wheat: "#d39a3a"
  wheat-deep: "#a8731f"
  poppy: "#c4553c"
  clay: "#c98a64"
  dusk: "#2c4636"
  dusk-ink: "#e9f0e6"
typography:
  display:
    fontFamily: "Young Serif, Georgia, serif"
    fontSize: "clamp(3rem, 8vw, 5.5rem)"
    fontWeight: 400
    lineHeight: 0.98
    letterSpacing: "-0.02em"
  headline:
    fontFamily: "Young Serif, Georgia, serif"
    fontSize: "clamp(1.9rem, 3.6vw, 2.6rem)"
    fontWeight: 400
    lineHeight: 1.1
    letterSpacing: "-0.01em"
  title:
    fontFamily: "Young Serif, Georgia, serif"
    fontSize: "clamp(1.6rem, 3vw, 2.1rem)"
    fontWeight: 400
    lineHeight: 1.15
  pitch:
    fontFamily: "Young Serif, Georgia, serif"
    fontSize: "clamp(1.3rem, 2.4vw, 1.65rem)"
    fontWeight: 400
    lineHeight: 1.3
  body:
    fontFamily: "Literata, Georgia, serif"
    fontSize: "1.0625rem"
    fontWeight: 400
    lineHeight: 1.65
  label:
    fontFamily: "Literata, Georgia, serif"
    fontSize: "0.9rem"
    fontWeight: 400
    lineHeight: 1.45
rounded:
  board: "6px"
  lane: "0"
  pill: "999px"
  round: "50%"
spacing:
  gutter: "clamp(1.25rem, 4vw, 2.5rem)"
  container: "1120px"
  section: "clamp(4rem, 9vw, 7rem)"
  stop: "clamp(2.5rem, 5vw, 3.75rem)"
  intro-gap: "2.5rem"
components:
  button-primary:
    backgroundColor: "{colors.betty-deep}"
    textColor: "{colors.snow}"
    rounded: "{rounded.pill}"
    padding: "0.75rem 1.35rem"
  button-evening:
    backgroundColor: "{colors.wheat}"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    padding: "0.75rem 1.35rem"
  fingerpost:
    backgroundColor: "{colors.snow}"
    textColor: "{colors.betty-deep}"
    rounded: "{rounded.board}"
    padding: "0.9rem 1.25rem 1rem"
    width: "20rem"
  lane:
    backgroundColor: "{colors.lane}"
    rounded: "{rounded.lane}"
    width: "2.75rem"
  portrait:
    rounded: "{rounded.round}"
    size: "5.5rem"
---

# Design System: Liv Allden

## Overview

**Creative North Star: "The Country Lane"**

The page is a slow drive through the countryside on a clear morning. The ground starts as pale sky (never cream), eases into meadow green as you scroll, and ends in a dark-green evening. Content sits directly on that ground with lots of air: no cards, no outlined boxes, no grid of tiles. The only objects that stand up off the land are things that belong in a lane: the lane itself, milestones beside it, white fingerposts carrying each role's headline result, and Betty the van driving down it.

Illustration is flat and quiet: softly layered hills in three greens, and small line drawings (a 2px hedgerow-ink outline over flat fills) of the things Liv loves: books, pottery, yarn, George and Ellie, and Betty. Type is all serif: Young Serif carries names, headings and figures; Literata carries reading text. The effect should be calm, warm and personal, while every title, company, date and number stays easy to scan.

The world was chosen to replace an earlier, rejected "granny-square blanket" direction because that one was too busy. Calm and simple win over decoration.

**Key Characteristics:**
- Sky-to-meadow vertical gradient ground; a dark dusk band closes the page.
- All-serif type: Young Serif display at weight 400, Literata body.
- No containers around content; depth comes from layered hills and a few soft-shadowed objects.
- Betty green carries the action; one wheat-ochre accent marks links, milestones and the evening button.
- Flat line-drawn motifs in hedgerow ink with flat fills.
- One signature interaction: Betty, seen from above, sticks to the lane as you scroll the career.

## Colors

A cool morning palette of sky, meadow and hedgerow greens, inked in deep green rather than black, with Betty's green and a single warm wheat accent.

### Primary
- **Betty Green Deep** (betty-deep): The primary button fill, the one-line pitch under the name, and fingerpost figures. It is the colour of action and of results.
- **Betty Green** (betty): Focus rings, accent-color and caret, and the van's body in motifs. Hover deepens the button to a darker Betty (#275c3c).

### Secondary
- **Wheat Ochre** (wheat): The single warm accent. Link underlines, milestone rings on the lane, text selection, the evening button, focus rings on the dark band. Hover lightens it on the evening button (#e0ab4f).
- **Wheat Deep** (wheat-deep): The fingerpost's wooden post only.

### Neutral
- **Morning Sky** (sky): The page ground behind the opening scene, held for the first 640px.
- **Meadow** (meadow): The ground from about 1400px down; the gradient eases between the two.
- **Hill Greens** (hill-1, hill-2, hill-3): The three layered hill fills, lightest at the back. hill-2 is the grass verge around the lane; hill-3 is the "How I work" band and the windowsill line under the motifs.
- **Hedgerow** (hedge): Trees in the landscape and the leaf bullets in role lists.
- **Lane** (lane): The road surface and its dashed centre line.
- **Hedgerow Ink** (ink): All primary text and every motif outline.
- **Soft Ink** (ink-soft): Secondary text: intros, dates, role periods, company descriptions, captions.
- **Snow** (snow): Betty's white, fingerpost boards, milestone centres, the portrait ring, button text.
- **Glass** (glass): Van windows in motifs.
- **Dusk** (dusk) and **Dusk Ink** (dusk-ink): The evening close and footer background, and its body text.

### Motif-only
- **Poppy** (poppy), **Clay** (clay), **Sky Deep** (sky-deep), plus Ellie's blue eyes and the cats' pink ears and nose, appear only inside illustrations.

### Named Rules
**The Motif-Only Rule.** Poppy, clay, sky-deep and the cats' blues and pinks are illustration fills. They never colour text, buttons, links, rules or backgrounds.

**The One Wheat Rule.** Wheat is the only warm accent in the UI. It marks links, milestones and the evening call to action, and nothing else competes with it.

**The Never Cream Rule.** The ground is sky and meadow. Warm paper, cream or beige grounds are not part of this world.

## Typography

**Display Font:** Young Serif (with Georgia, serif), self-hosted, weight 400 only
**Body Font:** Literata (with Georgia, serif), self-hosted variable 200 to 900, roman and italic

**Character:** Young Serif is round, friendly and slightly old-fashioned, like a village sign; Literata is a calm book face that keeps long CV prose comfortable to read.

### Hierarchy
- **Display** (Young Serif 400, clamp(3rem, 8vw, 5.5rem), 0.98, -0.02em): Liv's name in the opening scene only, left-aligned.
- **Pitch** (Young Serif 400, clamp(1.3rem, 2.4vw, 1.65rem), 1.3, balanced wrap): The one-line positioning statement, in Betty Green Deep.
- **Headline** (Young Serif 400, clamp(1.9rem, 3.6vw, 2.6rem), 1.1, -0.01em): Section titles.
- **Title** (Young Serif 400, clamp(1.6rem, 3vw, 2.1rem), 1.15): Company names at each stop. Fingerpost figures use the same face at clamp(1.6rem, 2.4vw, 2rem); home-thing headings at 1.3rem.
- **Body** (Literata 400, 1.0625rem, 1.65; 1rem under 560px): All reading text. Prose blocks cap at 34 to 44rem, about 62ch.
- **Role line** (Literata 600, body size): Job titles; the dates beside them in Literata italic 400, soft ink.
- **Label** (Literata 400, 0.9rem, 1.45): Fingerpost captions and the footer.

### Named Rules
**The Single Weight Display Rule.** Young Serif is only ever set at 400. Hierarchy comes from size and colour, never bold display.

**The Book Italic Rule.** Italic Literata in soft ink is the voice for secondary asides: dates beside roles and the "open to conversations" line. It never carries a heading.

## Layout

A single centred column, max 1120px with fluid gutters of clamp(1.25rem, 4vw, 2.5rem). Sections are separated by generous air (clamp(4rem, 9vw, 7rem)) rather than rules. Each section opens with a headline and a short soft-ink intro, then 2.5rem of space.

The opening scene puts text on the sky at left (max 38rem) with a full-width hill landscape bleeding underneath it, pulled up beneath the text with a negative margin. "How I work" is a full-bleed hill-3 band with a 1:2 heading-to-text grid that stacks under 900px.

The journey indents content from a vertical lane at the left (indent clamp(4.5rem, 10vw, 8rem); 3.5rem on phones). Each role is a stop with clamp(2.5rem, 5vw, 3.75rem) below it. At 1100px and wider a stop becomes two columns: content up to 42rem and a 17rem fingerpost column; below that the fingerpost sits inline after the role lines.

The "end of the lane" is a five-across row of motifs sitting on a shared windowsill line; it drops to two columns (last item full width) under 900px. The page closes on a full-bleed dusk band with a curved hill top, centred text and the wheat button.

Breakpoints: 560px (phone tightening), 900px (stacking), 1100px (fingerpost column).

## Elevation & Depth

Depth is mostly landscape: three overlapping flat hill layers and a pale distant hill do the work. Content itself is flat on the ground. A small set of real-world objects carry soft, diffuse, ink-tinted shadows to sit up off the land: the portrait, the primary button, the fingerpost boards and Betty on the lane. All shadows are downward, blurred and tinted with ink or Betty green, never black and never hard-edged.

### Shadow Vocabulary
- **Portrait lift** (`box-shadow: 0 6px 18px -8px rgba(33, 52, 41, 0.45)`): The round photo.
- **Button lift** (`box-shadow: 0 6px 16px -8px rgba(47, 110, 72, 0.7)`, hover `0 10px 20px -10px rgba(47, 110, 72, 0.8)`): Primary button on light ground. None on the dark evening band.
- **Fingerpost** (`box-shadow: 0 1px 0 rgba(33, 52, 41, 0.08), 0 8px 18px -10px rgba(33, 52, 41, 0.35)`): The white result boards.
- **Van on the lane** (`filter: drop-shadow(0 4px 4px rgba(33, 52, 41, 0.25))`): Betty from above.

### Named Rules
**The Objects Only Rule.** Only things that exist in the lane (photo, button, fingerpost, van) get a shadow. Text blocks, sections and lists never do.

## Shapes

Soft and organic. The lane is one continuous strip with 5px hill-2 grass verges either side and a dashed white centre line; it has square ends because it never stops: it leaves the hills at the top and fades out (a mask) as it reaches home. Milestones are 1.1rem circles: a snow centre, a 3px wheat ring and a lane-coloured halo. Fingerposts are 6px-rounded white boards; at desktop width they gain a pointed end aimed back at the lane and a wheat-deep post planted below. Buttons are full pills. The portrait is a circle with a 3px snow ring. List bullets are small hedgerow leaves (an eye shape rotated -20deg). Hill silhouettes are long, low curves.

Motifs are line drawings at a 2px hedgerow-ink outline with rounded joins over flat fills; heavier strokes (2.5 to 4px) are used only for solid forms such as tails, handles and needles.

## Components

### Buttons
Friendly, solid and pill-shaped.
- **Shape:** Full pill (999px).
- **Primary:** Betty Green Deep fill, snow text, Literata 600, padding 0.75rem 1.35rem, an inline LinkedIn mark at 1.05rem and a 0.55rem gap.
- **Hover / Focus:** Darkens to #275c3c, rises 1px and the shadow deepens over 0.3s on the shared ease-out curve (cubic-bezier(0.16, 1, 0.3, 1)). Focus is a 2px Betty outline offset 3px.
- **Evening:** On the dusk band the same pill is wheat with ink text and no shadow; hover lightens to #e0ab4f; focus ring turns wheat.

### Links
Inherit text colour with a 1.5px wheat underline offset 0.2em; the underline turns Betty green on hover. Company names at stops are not underlined until hover.

### Navigation
A quiet single row: Liv's name in Young Serif 1.25rem at left, a plain "LinkedIn" text link at right, baseline-aligned. No menu, no background, no border.

### Fingerpost (signature)
A white board beside each stop carrying its headline result: a Young Serif figure in Betty Green Deep, with a 0.9rem soft-ink caption underneath. Max 20rem wide. From 1100px it moves to its own column with a pointed end and a wooden post. Only roles with a real, quotable result get one.

### The Lane and Betty (signature)
One lane runs the whole trip. In the opening landscape it winds down out of the hills; a small inline script in `src/index.html` redraws the hill lane (and Betty's position on it) so it leaves the bottom of the scene exactly where the 2.75rem timeline lane sits, recalculating on resize. The lane then runs straight down the left through "How I work" and every stop (the `.trip` wrapper holds it), with a milestone at each stop, and fades out at "At the end of the lane". Without JavaScript the hill lane falls back to its drawn shape. Scrolling is the drive: side-view Betty travels down the hill lane with scroll progress (tilted to its slope), then cross-fades into top-down Betty, who is sticky at 45vh inside the timeline lane. As she passes each stop its milestone fills wheat and, from 1100px, its fingerpost swings upright from a slight lean.

### Home Things
Five motifs at 7.5rem tall (6rem on phones) on a shared hill-3 windowsill line, each with a Young Serif 1.3rem heading and a short soft-ink line.

### Living landscape
The opening sky follows the visitor's local time (`html[data-daypart]`): a pale morning sun, a higher afternoon sun on a bluer sky, a low orange evening sun behind the far hills with a peach glow, or a crescent moon and faint stars at night. Text stays dark ink in every daypart, so the sky palettes stay light. The far hill layers drift a few pixels with the cursor (fine pointers only), clouds drift slowly, and George flicks his tail every few seconds. The evening close has a rising crescent moon and a few twinkling stars.

### Motion
The opening text settles up 12px once, staggered 60ms per line over 1.1s on the ease-out curve. Every transition uses the same exponential ease-out; nothing bounces or overshoots. All motion sits inside prefers-reduced-motion: no-preference; with reduced motion both vans stand still and every milestone and fingerpost is shown at rest.

## Do's and Don'ts

### Do:
- **Do** set content directly on the sky and meadow ground, separated by air (clamp(4rem, 9vw, 7rem) between sections).
- **Do** use Young Serif at 400 for names, headings, company names and figures, and Literata for everything read.
- **Do** keep Betty Green Deep for the primary action and results, and wheat as the single warm UI accent.
- **Do** draw new motifs as 2px hedgerow-ink outlines over flat fills taken from the palette.
- **Do** put a role's headline number on a fingerpost, not in a styled callout inside the prose.
- **Do** keep all motion inside prefers-reduced-motion: no-preference.

### Don't:
- **Don't** put content in cards, bordered boxes or tile grids; the fingerpost is the only board in the world.
- **Don't** use poppy, clay, sky-deep or the cats' blues and pinks outside illustrations.
- **Don't** use cream, beige or warm-paper grounds.
- **Don't** bold Young Serif or set display type in a sans or system face.
- **Don't** add hard-edged, offset or black drop shadows; drop shadows are soft, downward, ink- or green-tinted, and only on lane objects. (The lane's 5px verges are borders, and the milestone's lane halo is a zero-offset spread ring drawing the land, not a shadow.)
- **Don't** bring back granny-square, patchwork or blanket patterns.
