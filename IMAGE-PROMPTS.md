# Keep Your Heart — Image Prompt Sheet

Drop finished images into `assets/img/` using the **exact filenames** below. Every
slot degrades gracefully: if a file is missing, a layered gradient renders in its
place and the page still looks intentional. So generate them in any order, and a
half-finished set will never look broken.

**Format:** wide crops. Heroes read at roughly 3:1 on desktop, so compose with the
subject slightly above centre — the bottom third is covered by a navy scrim that
carries the page text. Plates read at roughly 2:1.

---

## House style preamble

Paste this in front of every prompt so the set coheres:

> Painterly digital illustration in the manner of a mid-century book plate. Warm
> parchment and deep navy palette with amber-gold accents. Muted, slightly desaturated,
> visible brush texture. Soft directional light, no harsh contrast. Contemplative and
> quiet, never dramatic or glossy. No text, no lettering, no watermarks, no human faces
> in close-up. Wide horizontal composition.

Two rules worth holding to across the whole set, because the subject matter makes it
easy to drift: **no faces in close-up** — figures should be distant, turned, or
implied, so the reader is never told what suffering looks like. And **nothing bleak.**
Every image should have a light source in it somewhere. The book argues that the dark
is not the last word; the art should not contradict it on the way in.

---

## Built pages

### `hero.jpg` — site hero
> A narrow footpath running through long grass toward a distant lit doorway at dusk.
> Low golden light on the horizon. The path is uneven and partly overgrown but clearly
> continuous. Vast quiet sky.

*Why:* the whole book in one image — a real path, real difficulty, a destination that
is already lit and already open.

### `ch01.jpg` — All Truth Is God's Truth
> A single sheaf of ripe wheat standing in an open field under scattered rain, with
> sunlight breaking through the cloud on one side. Rain and light falling together over
> the same ground.

*Why:* Matthew 5:45, rain on the just and unjust. The image should feel like generosity
rather than judgment.

### `ch02.jpg` — The Engine Problem
> A warmly lit farmhouse doorway seen at night from out in the dark yard, with a long
> table and lamplight visible inside. In the foreground, at the edge of the light, an
> empty chair turned away from the house.

*Why:* the elder brother standing outside the party. The door is open. Nobody is
stopping him.

### `ch03.jpg` — Why You Hurt
> A stone wall in soft rain with moss and a deep crack running through it, and a single
> small green shoot growing directly out of the crack. Grey-green light, but the shoot
> is clearly lit.

*Why:* real damage, not minimized, and something alive in it anyway. Avoid anything
that reads as a metaphor for a person being broken *by their own fault*.

### `ch03-plate.jpg` — Timothy Rogers
> A seventeenth-century study at night: a plain wooden desk, a guttering candle, an open
> book, an unmade cot in the shadowed corner. Nobody in the room. The chair pushed back.

*Why:* the two years Rogers lost. The empty room does the work; a portrait would not.

### `ch04.jpg` — Both/And Without Losing the Floor
> A Roman stone arch photographed from below, the two curving sides leaning inward
> against each other with the keystone at the top. Warm afternoon light. The structure
> obviously bearing weight.

*Why:* an arch is the perfect image for the chapter — two forces pushing against each
other, and that opposition is precisely what holds the load. Nothing is balanced; it is
locked.

### `ch04-plate.jpg` — Chalcedon
> An ancient stone boundary marker or low drystone wall running across an open green
> field, with wide unbroken country on both sides of it. Overcast silver light.

*Why:* the creed as a fence around a mystery, not an explanation of it. Note the field
should look *spacious* — the fence is not a cage.

---

## Queued (generate whenever, slots not yet live)

| File | Chapter | Prompt subject |
|---|---|---|
| `ch05.jpg` | Before the Face of God | A window seat with morning light falling across an open book and a cooling cup; the room turned toward the light rather than inward. |
| `ch06.jpg` | Talk to Yourself | A person seen from behind, small in frame, standing at a shoreline speaking toward open water at dawn. |
| `ch07.jpg` | Filled, Not Emptied | A stone cistern brimming and overflowing with clear water into a garden, rather than an empty vessel. |
| `ch08.jpg` | Examined but Not Absorbed | A hand-held mirror lying face-up on a table, reflecting a window rather than a face. |
| `ch09.jpg` | The Cup and the Garden | An olive grove at night under a heavy moon, ancient gnarled trunks, one patch of ground disturbed. No figure. |
| `ch10.jpg` | Lament | Rain on a stone church step at night with warm light spilling out of the half-open door behind it. |
| `ch11.jpg` | Bread and Sleep and Sabbath | A loaf, a water jar, and a folded cloak under a solitary desert broom tree at first light. |
| `ch12.jpg` | The Key of Promise | An iron key lying in an open palm in a shaft of light through a barred window; the door itself out of frame. |
| `ch13.jpg` | Ordered Affections | An overgrown formal garden being brought back into order, half wild and half pruned, in late light. |
| `ch14.jpg` | Truth in Love | Two chairs turned toward each other across a small table by a window, both occupied-looking but empty. |
| `ch15.jpg` | Burdens and Loads | Two figures at a distance on a hill path, one carrying a pack, the other reaching back a hand. |
| `ch16.jpg` | A Life You Did Not Build | A long table laid and lit in an orchard at golden hour, places set, nobody seated yet. |

---

## Adding art to the site

1. Save as `.jpg` into `assets/img/` with the exact filename.
2. Rebuild is not required — the slots are already in the HTML.
3. If a filename does not match, nothing breaks; the gradient simply stays.
