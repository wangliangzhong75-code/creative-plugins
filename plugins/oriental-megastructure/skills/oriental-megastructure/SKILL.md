---
name: oriental-megastructure
description: "Generate, diagnose, and refine copy-ready Midjourney prompts for minimalist Eastern celestial megastructures: monumental Tang-Song-inspired architecture, tiny human scale references, large negative space, and restrained cinematic color. Use for 天宫、云上天宫、东方神域、东方巨构 or related Midjourney prompt requests; do not use for general architecture prompts or direct bitmap generation."
---

# 东方极简巨构

Create copy-ready Midjourney prompts that preserve the user's established “极简东方天宫巨构美学.” The architecture is the absolute subject: fewer structures, larger mass; smaller people, stronger scale; fewer elements, greater divinity.

This skill writes or critiques prompts. It does not submit Midjourney jobs or generate bitmap images.

## Modes

Choose the mode implied by the request:

- **Generate:** Create distinct prompts from a theme, place, object, cultural motif, or short brief.
- **Diagnose:** Explain why an image or prompt lacks scale, simplicity, or Eastern monumental character, then provide a corrected prompt.
- **Adapt:** Preserve the style system while changing the setting, architecture, natural phenomenon, time, or mood.

Do not ask for clarification when a reasonable visual interpretation is possible. Preserve any aspect ratio, scene count, subject, Midjourney parameters, or exclusions the user supplies.

## Non-negotiable visual system

### One monumental subject

- Use one core palace, gate, hall, bridge, corridor, altar, courtyard, observatory, or related structure.
- Make it mountain-, city-, wall-, or continent-scale. It should occupy roughly 70%–90% of the frame and may extend beyond the top and side edges.
- Treat architecture as landscape, not as a decorative background.
- Use a clean, legible silhouette: one immense roof, one massive wall or opening, a few colossal columns, and restrained ornament.
- Favor Tang-Song-inspired proportions: broad dark roofs, controlled flying eaves, vermilion massing, weathered timber, white jade, black stone, and aged bronze.
- Avoid palace clusters, rows of small pavilions, stacked roofs, dense eaves, busy carvings, tourist-site staging, game-like xianxia decoration, and cyberpunk technology.

### Extreme human-to-building scale

- Include at most one person unless the user asks otherwise.
- Keep the person around 0.3%–1% of the frame: a solitary dot or tiny robed traveler used only as a scale reference.
- Do not let facial detail, costume detail, action, or portrait framing compete with the architecture.

### Deliberate subtraction and negative space

- Besides the main structure, allow at most one path, stair, bridge, or platform and one natural or cosmic phenomenon.
- Build negative space from an endless cloud sea, empty sky, deep space, cyan mist, a black mirror-stone platform, or a straight white-jade road.
- Keep the scene quiet, sparse, sacred, and readable. Remove any element that does not strengthen scale, depth, or atmosphere.

### Composition

- Default to a 9:16 vertical frame for “竖屏” or when no ratio is specified.
- Prefer an ultra-wide lens, low-angle view, strong central vanishing point, or near-symmetrical composition.
- Let the building continue outside the frame so its full extent cannot be seen.
- Use roads, stairs, bridges, corridors, or platforms only as clean leading lines.
- Keep the camera stable and the geometry intentional; avoid cluttered Dutch angles and casual eye-level tourism views.

### Color, light, and material

- Limit the palette to vermilion, black, white, pale cyan/blue-gray, and a small amount of antique gold.
- Use cool celestial or moon light as the base with sparse warm amber light inside the structure.
- Add volumetric mist, soft cloud layers, atmospheric perspective, diffused highlights, restrained bloom or halation, and subtle film texture when they support cinematic depth.
- Describe realistic scale-bearing materials: weathered timber, monumental stone, wet black stone, white jade, patinated bronze. Material detail may be rich, but structural form must remain simple.
- Aim for sacred silence, mystery, ancient civilization, poetic loneliness, and IMAX-scale cinematic realism rather than glossy fantasy illustration.

## Scene differentiation

When generating multiple prompts, make each scene structurally different. Vary at least three of these dimensions instead of merely changing names or colors:

- spatial archetype: isolated hall, vertical gate, suspended corridor, ring courtyard, broken bridge, celestial altar;
- dominant geometry: horizontal slab, vertical opening, circle, causeway, abyss, monolithic wall;
- one phenomenon: cloud ocean, waterfall, giant moon, pale planet, eclipse, deep-space aperture;
- approach and viewpoint: frontal ascent, interior low angle, distant causeway, beneath the structure, across a void;
- emotional register: sacred dawn, blue-hour solitude, moonlit ritual, post-civilization stillness.

Do not repeat the same “palace + moon + person” composition across every prompt.

## Midjourney prompt construction

Write each English prompt as one continuous copy-ready block in this order:

1. single architectural subject and setting;
2. simple structural form and Tang-Song cues;
3. explicit building/frame and person/frame scale;
4. limited path/platform and one phenomenon;
5. composition, lens, viewpoint, and depth;
6. restrained palette, light, atmosphere, and realistic materials;
7. emotional and cinematic finish;
8. Midjourney parameters and negative constraints.

If the user does not provide parameters, use the restored baseline:

~~~text
--ar 9:16 --style raw --s 175 --chaos 3
~~~

End with a focused negative list, adapting it to the scene:

~~~text
--no text watermark logo crowds dense buildings palace clusters small pavilions stacked roofs excessive carvings ornamental clutter busy background neon cyberpunk modern technology
~~~

Do not add /imagine. Do not put commentary inside the prompt block. Do not invent version-specific parameters that the user did not request.

## Output contract

For generation:

- Default to four scenes when the user asks for a set without specifying a count.
- Give each scene a concise Chinese title.
- Optionally add one short Chinese sentence explaining the scene's distinguishing visual device.
- Put exactly one complete English Midjourney prompt in a fenced text block beneath each title.
- Keep every prompt directly copyable and self-contained.
- After the prompts, add at most one concise usage note only when it materially helps.

For diagnosis:

1. Briefly assess subject count, architecture/frame ratio, person/frame ratio, silhouette complexity, negative space, viewpoint, color, and competing details.
2. Name the two or three highest-impact corrections.
3. Return one fully rewritten copy-ready prompt.

For adaptation, state the preserved visual DNA in one sentence, then return the requested prompts without repeating the full style theory.

## Quality check

Before responding, verify:

- one dominant structure, not a building collection;
- architecture visibly outweighs every other element;
- the person is optional, solitary, and nearly invisible;
- only one leading element and one phenomenon remain;
- negative space is intentional and substantial;
- Tang-Song cues are clear but not ornate;
- the scenes differ in geometry and spatial experience;
- every prompt is immediately copyable and includes compatible parameters.
