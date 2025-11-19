# Sigilizer — Phase B Rules (Structure & Mapping)

Phase B selects the appropriate structural grid (kamea) and maps the reduced
numeric sequence to it. The result is a path-based symbol that can be rendered
with or without the underlying grid.

## 1. Planetary Selection

Choose a planetary kamea based on the category of the intention. For example:

- **Saturn** – structure, discipline, endings
- **Jupiter** – growth, opportunity, expansion
- **Mars** – protection, conflict, courage
- **Sun** – visibility, vitality, leadership
- **Venus** – relationships, aesthetics, harmony
- **Mercury** – study, communication, commerce
- **Moon** – intuition, memory, emotional life

(These categories can be adjusted to match the practitioner’s system.)

## 2. Kamea Compatibility Check

Each kamea has a maximum cell value (e.g., 9 for a 3×3 square). If any Phase A
numbers exceed that maximum:

- Reduce the number by **removing trailing zeros** (e.g., 40 → 4, 90 → 9).
- Do **not** use digit-sum reduction unless explicitly specified.

After reduction, every number in the sequence must correspond to a valid cell
on the chosen grid.

## 3. Path Construction

1. Identify the cell for each number on the kamea.
2. Plot the sequence in order:
   - Draw a line from the first number to the second, second to the third, and
     so on, without lifting the pen.
3. Mark:
   - The **start point** with a circle.
   - The **end point** with a short **perpendicular cap**.

If the same number appears consecutively, you may:
- Emphasize it with a small loop, or
- Treat it as a “rest” or emphasis point on the same cell.

## 4. Output Variants

Produce at least two renderings:

- **Grid Version**  
  The kamea grid and numbers are visible under the path, useful for checking
  correctness and teaching the method.

- **Clean Sigil Version**  
  Only the final path is shown, without the grid or numbers, suitable for use
  as a symbol or engraving.

## 5. Usage Notes

- This specification focuses on the **algorithmic structure** of the workflow.
- The same method can be implemented as:
  - Manual drawing instructions
  - A programmatic generator (e.g., SVG export)
  - A Custom GPT workflow that outputs drawing coordinates

Phase B is complete when the numeric sequence has been mapped to a path that
can be consistently reproduced from the same input phrase.
