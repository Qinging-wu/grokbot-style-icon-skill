# Style specification

This guide records the reusable visual rules learned from repeated generations and user corrections. The user’s newest instruction overrides this guide. If two generic rules conflict, use the priority order at the end.

## 1. Face direction and roll — highest risk

- The face looks straight at the viewer: frontal, direct gaze, no side view, three-quarter view, head yaw, or perspective foreshortening.
- Roll the complete head group in the image plane about **15° clockwise** (acceptable range 12–18°). Rotate the head, face, hair, eyes, blush, and accessories together. Do not simulate this by turning the face sideways.
- Verify the screen direction explicitly: **the eye on the image-left is higher than the eye on the image-right**. The line between eye centers slopes downward from left to right. Never reverse this.
- In face-local coordinates, both capsule eyes remain vertical, parallel, equal in size, and symmetrically placed. Because the face is rolled, the eyes also appear rolled in the canvas. Do not straighten each eye independently.

## 2. Composition — highest risk

- Square 1:1, extreme close-up mascot portrait. Place the character toward the **lower-left**, not centered. Aim for the face center at roughly 35–42% of canvas width and 58–68% of canvas height.
- Let hair and face naturally crop at the left and bottom edges. Keep both eyes fully visible.
- Preserve a clean, continuous dark charcoal area in the upper-right, around 20–25% of the canvas. Keep hair, accessories, and shoulders out of this negative space.

## 3. Skin tone — match the source

- Match the reference face’s base value (lightness) and undertone. Do not normalize every character to the same pale cream tone.
- Very fair skin must remain very fair; medium or darker skin must not be bleached. Avoid unrequested yellow, peach, orange, pink, or brown shifts.
- Use a mostly even flat base with restrained shading. Blush must remain two separate cheek marks, not a wash that recolors the whole face. Visible neck skin should match the face.

## 4. Face marks and blush

- Show only two eyes and two blush marks. Eyes are matching solid-black vertical capsules with rounded ends, approximately 3:1 height-to-width; no iris, pupil, sclera, highlights, eyeliner, brows, or lashes.
- Keep the pair symmetrical in face-local coordinates. Their long axes are parallel to each other and follow the rolled face.
- Put one soft pink oval on each cheek below the eyes. Move each blush slightly outward toward its corresponding cheek, while keeping clear of the face edge and hair. Match their scale and color; their long axes are parallel in face-local coordinates and rotate with the face.
- Do not add a nose, mouth, or other facial marks unless the user explicitly asks.

## 5. Clothing and shoulders

- Keep a short neck, only a small amount of shoulder, and a recognizable piece of the current character’s collar, lapel, bow, uniform, or scarf at the bottom edge. Clothing should be visible enough to establish that the character is dressed.
- Do not erase the clothing into bare shoulders. Do not expand the crop into a bust or torso portrait. Keep the clothing fragment restrained (about 12–18% of the bottom area).

## 6. Hair, accessories, and rendering

- Preserve the current character’s hair color, outer silhouette, and distinctive structural details. A looped, braided, tied, or unusually curled lock is part of the hairstyle, not automatically an accessory; inspect how it connects to the main hair before simplifying it.
- Keep only one or two identity-defining accessories, simplified into flat shapes. Do not invent details or let ornaments invade the upper-right negative space.
- Use soft, matte, mostly flat 2D anime mascot coloring with a few coherent hair shapes. Limit gradients, shine, tiny strands, and complex shadows. Use a plain dark charcoal/near-black background without texture, frame, card, logo, or watermark.

## 7. Negative constraints

Avoid: a turned or off-center face; mismatched eye size or angle; reversed roll (right eye higher); upright head; eyes independently straightened; centered/right-heavy composition; filled upper-right space; cropped eyes; missing clothes; excessive shoulders or torso; skin tone drift; full body; hands, weapons, or non-identity props; extra facial features; text, logo, watermark, particles, 3D realism, heavy outlines, or elaborate background.

## Final visual check

Before presenting the result, check these in order:

1. Does the skin match the source lightness and undertone?
2. Is the face frontal and making eye contact?
3. Is the whole head rolled clockwise, with image-left eye higher than image-right eye?
4. Are the eyes parallel in face-local coordinates and rotated together with the face?
5. Is the character in the lower-left with clean dark negative space in the upper-right?
6. Are the blushes slightly outward, and are the neck, small shoulders, and clothing cue present?
7. Does the hair preserve this character’s distinctive silhouette and strand structure?

Priority when generic constraints compete: **frontal gaze and roll direction → lower-left composition and upper-right negative space → source-matched skin tone → eye/blush geometry → recognizable clothing → hairstyle and accessories**. A direct user correction takes precedence over all of these.
