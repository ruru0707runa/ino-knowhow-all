# Canva Browser Workflow

Read this only when operating Canva through browser automation.

## Reliable interaction rules

- Start from Canva's visible “new design” flow or a fresh blank preset, then resize in place. Do not duplicate a prior design.
- Inspect the current accessibility state before acting; control identifiers change between sessions.
- Use keyboard shortcuts only while the canvas has focus: `r` creates a rectangle, `t` creates text, and `l` creates a line.
- After adding an element, wait for its selection toolbar to appear before changing dimensions or color.
- Position elements through Canva's **Position** panel using width, height, X, Y, and rotation fields.
- Preserve image aspect ratio. For rectangles, turn the ratio lock off when setting width and height independently.
- Select the full text value before changing font, weight, size, or color so formatting applies to the whole string.
- Verify the text editor value after each insertion; remove any leftover placeholder text.
- Add large background shapes before foreground media and text to keep layer order predictable.
- Reinspect the full canvas after a batch of edits. If an operation visibly failed, correct the selected element instead of repeating blind clicks.

## Image handling

- Use the Uploads panel and match filenames exactly.
- Apply Background Remover only to the portrait.
- Do not crop the cover when the goal is to show the entire book design.
- If a Canva mockup introduces a colored background, blur, or unrelated props, undo it and use the flat cover with a spine/page strip.

## Completion checks

- One page at the intended dimensions
- No selected or editing state obscuring the final view
- All required text visible in the accessibility tree or canvas
- “All changes are saved” visible before returning the link
- Mark or retain the created browser tab as the deliverable when the environment supports it
