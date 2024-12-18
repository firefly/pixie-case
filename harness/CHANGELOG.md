Changelog
=========

Since SketchUP files don't diff well, this log serves as a history of
the changes made between harness versions.

v5; 2024-10-06
--------------

- Remove display end retaining ledge and add display retaining nib

v4; 2024-08-24
--------------

- Added deeper retaining ledge.
- Increased gap around buttons.

v3; 2024-06-25
--------------

- Move display cover back to 1.2mm as there was a triangle of warping near the USB port in it
- Extend the top and bottom wall for the LCD 0.1mm since the fir was very snug
- Use 0.5mm tabs (v3 experimented with 0, 0.5 and 1mm; 0.5 worked well)
- Move tabs (board and LCD) further from the corners which made board insertion crack the nibs
- Broke board tabs into multiple sections for simpler assembly

v2; 2024-06-21
--------------

- Extend the case 1mm past the bottom of the board and add snap fit clips
- Move buttons and LEDs 2mm towards the right edge (reflected in the rev.6 PCB)
- Reduce the thickness between the PCB and top of button shelf, which interferes with button travel
- Remove LED holes, since the 8001 clear resin is clear enough
- Add sill for display; optionally add nibs

v1; 2024-06-04
--------------

- Initial design after many reported concerns by the printhouse (JLCPCB)
- The goal is to have a backup MVP
- The initial print tests the transparency of the 8001 clear resin
- Two versions; with a display hole (printed in multiple colors) and without a display hole (only with transparent resin)
