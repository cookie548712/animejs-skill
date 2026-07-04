---
description: Guidance for anime.js projects when building or reshaping UI, examples, and motion-led interfaces. Helps with visual direction, typography, layout, motion structure, and avoiding generic demo patterns.
license: Complete terms in LICENSE.txt
---

# Anime.js Frontend Design Skill

Approach this project as a motion-first design system for a technical showcase site. The goal is not to make a generic animation demo, but to create a distinct visual identity where layout, typography, color, motion, and interaction all serve the same idea: clear, structured, intentional animation expression.

## Ground it in the subject

If the brief is vague, pin it down before designing. Name the page type, its audience, and the single job it must do. Then choose the visual strategy that best fits that job. For this project, prefer a technical, experimental, and highly structured tone. The subject matter should come through in the motion system itself: timelines, paths, text transformations, drag behavior, scroll reveals, layered cards, canvas drawing, and 3D spatial motion.

Use the project’s own world as the design source. The examples are not random demos; they are a catalog of motion behaviors. Build around that catalog rather than defaulting to a generic hero + card grid pattern.

## Design principles

### Project identity

- Motion is the subject, not decoration.
- The interface should feel like a visual laboratory, not a marketing site.
- Keep the composition disciplined, technical, and intentional.
- Let the page feel like an engineered demonstration of animation capabilities.
- Make every choice look specific to this project, not reusable across any random product.

### Visual tone

- Default to dark, low-noise backgrounds with high-contrast foregrounds.
- Use the mono / grid / technical aesthetic as the base language.
- Keep color restrained at the system level and use accent colors only when they communicate structure or state.
- Favor clean surfaces, subtle shadows, and controlled borders over decorative gradients.
- Preserve a sense of engineering precision and experimental clarity.

### Typography

- Use a mono or technical type system for labels, captions, code-like metadata, and supporting text.
- Keep type scale intentional and restrained; avoid decorative hierarchy for its own sake.
- Use typography to reinforce function: labels label, captions annotate, headlines define the idea.
- Prefer compact, readable phrasing over clever copy.

### Layout

- Treat layout as content.
- Use grids, centered compositions, sticky panels, long scroll scenes, and modular cards as structural tools.
- Let the page explain itself through arrangement rather than ornament.
- When the motion requires it, make the layout behave like a timeline or a stage.
- Use whitespace deliberately so the animated subject has room to breathe.

### Motion

- Motion should reveal structure, not conceal it.
- Prefer orchestrated sequences over scattered effects.
- Use stagger, morph, draw, scale, translate, rotate, and opacity changes as coordinated layers of meaning.
- A strong entry sequence usually beats many small effects.
- Match motion complexity to the vision: minimal pages need precision, maximal pages need disciplined orchestration.

### Content and copy

- Write from the user’s side of the screen.
- Use plain, active language.
- Keep labels and buttons specific and functional.
- If copy is missing, create concise content that supports navigation and understanding.
- Do not let text become decoration; it should always clarify what the page is doing.

## Process: plan, critique, build, critique again

Work in two passes.

1. **Plan the design**: identify the example category, choose the palette, define the typography roles, and decide the layout concept and signature motion.
2. **Critique the plan**: check whether the result reads like a generic default. If it does, revise it until it feels specific to this project and this brief.

Use the brief’s own constraints first. When the brief leaves room, do not spend that freedom on a templated look. Choose a direction that feels engineered, subject-driven, and memorable.

## Example families and their design ideas

### `auto-layout` — layout as a rule system

Use when the layout itself is the demonstration.

- Make the arrangement communicate the behavior.
- Keep alignment, spacing, and hierarchy strict.
- Use grids, columns, lists, cards, and split panels to show structural variation.
- The UI should stay out of the way of the content’s logic.

### `text` — text as material

Use when characters, words, or lines are the animated subject.

- Treat text as something to be split, scrambled, revealed, masked, or restaged.
- Preserve legibility while transforming the sequence.
- Use hover, scramble, split, and reveal patterns to show semantic change.
- The effect should feel like information being uncovered, not text being destroyed.

### `svg` — contours, strokes, and morphing forms

Use for logos, line systems, graphs, diagrams, and shape transitions.

- Emphasize the construction process.
- Use draw, morph, path, and stroke as the expressive vocabulary.
- Keep shape changes readable and purposeful.
- Let the line become form, and the form become identity.

### `timeline` — motion as narrative structure

Use when the sequence itself is the point.

- Treat the timeline as the skeleton of the page.
- Make overlaps, offsets, loops, and transitions readable.
- Use playback and loop behavior as part of the design language.
- Structure matters more than spectacle.

### `draggable` — touch, drag, and physical response

Use when user gesture is part of the story.

- Make the interface feel grabbable, movable, and physically responsive.
- Show bounds, momentum, snapping, and continuous motion clearly.
- Keep feedback immediate and legible.
- The experience should feel like exploration.

### `onscroll` — scroll as time and scene change

Use when the page is a continuous reveal.

- Use sticky sections, spacers, and long scenes to stage the experience.
- Make scrolling feel like progression through scenes, not just page travel.
- Preserve orientation so users know where they are in the sequence.
- Keep the main subject centered and readable as the scroll advances.

### `canvas` — continuous drawing over static layout

Use when drawn output should dominate the page.

- Favor procedural marks, particles, paths, and motion trails.
- Let the drawing process be the main event.
- Keep the surrounding UI quiet and minimal.
- Prioritize continuity, smoothness, and performance.

### `threejs` — spatial order in 3D

Use when depth and camera motion matter.

- Build the design around spatial composition, not flat panels.
- Use perspective, rotation, scale, and camera movement as design tools.
- Keep the UI minimal so the 3D scene remains dominant.
- Make the motion in space feel intentional and readable.

### `additive` — layered growth and accumulation

Use when richness should emerge through layers.

- Build visual complexity by accumulation, not one big burst.
- Let multiple subtle changes create a living surface.
- Keep the effect organic and controlled.
- Favor ongoing growth over a single completed moment.

### `stagger` — ordered difference

Use whenever a group of elements needs rhythm.

- Avoid synchronized starts unless sameness is the point.
- Use stagger to create hierarchy, direction, and group identity.
- Delay is a structural tool, not just a timing trick.
- Use from / center / last / reversed strategically.

### `animatable` — objects that feel responsive

Use when the target should feel alive to input.

- Make motion feel like a direct response to the user.
- Show the response center and motion trail clearly.
- Keep the interaction immediate and comprehensible.

### `irregular` — non-uniform timing for realism

Use when the effect should feel organic rather than machine-perfect.

- Introduce variation, jitter, perturbation, or uneven pacing with restraint.
- Use irregularity to suggest hand motion, typing, breathing, flicker, or natural drift.
- Do not let irregularity become noise.

### `clock` and `playback` — control as part of the experience

Use when users should inspect, pause, rewind, or change speed.

- Make controls feel coherent with the visual state.
- Show time, direction, and progress clearly.
- The control surface should feel like part of the demo, not a separate add-on.

## Review checklist

Before finalizing, check the design against these questions:

- Does it feel specific to an anime.js showcase project?
- Is the subject of the page obvious within the first moment?
- Does the motion reveal structure instead of hiding it?
- Are the type, color, and layout choices deliberate rather than templated?
- Is the signature element memorable without overwhelming the rest?
- Does the final state feel clean, stable, and understandable?

## Final constraints

- Avoid generic marketing layouts.
- Avoid decorative motion that does not improve understanding.
- Avoid overly saturated color systems unless the brief truly calls for them.
- Avoid unnecessary complexity when the subject is minimal.
- Avoid arbitrary decoration that does not support the brief.

## Reusable keywords

- Motion-first
- Technical showcase
- Grid discipline
- Structured reveal
- Orchestrated sequence
- Text as material
- Layout as content
- Path as form
- Timeline as narrative
- Drag as exploration
- Scroll as scene change
- Canvas as continuous drawing
- 3D as spatial order
- Additive layering
- Staggered rhythm
- Irregular realism
- Playback as control
