# Scale Drawing Studio

Math 2201, Unit 6: Proportional Reasoning. Indicators 6.1, 6.2, 6.3, 6.4 and 6.12.

A formative practice app with two modes:

- **Measure and Find k**: students measure a drawn side of a diagram with an on-screen ruler, convert the matching actual length, state the scale factor using the house convention k = diagram measurement / actual measurement, then find an unknown side in either direction. Feedback names the likely error (direction reversed, unit mix-up, arithmetic slip).
- **Draw to Scale**: a grid drawing canvas (0.5 cm snapping) where students draw a rectangle to a stated scale, by dragging, by arrow keys, or by exact keyboard placement. Tasks state the scale three ways: a per form (1 cm represents R metres), a ratio form (scale 1 to N) and an image-under-k form. Checks name the likely error (dimensions swapped, wrong scale direction, one side only, arithmetic slip).

The print sheet carries the drawn diagram, a measurements table and the student's own scale statement, so it can be submitted as the scale diagram artifact for the unit inquiry assignment.

Single self-contained `index.html`, no external dependencies. `harness.js` independently recomputes the mathematics (81,093 assertions, PASS).

Live (once Pages is enabled): https://cdli-nlschools.github.io/ScaleDrawingStudio/
