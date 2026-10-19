# Classroom Seating Studio

A reusable browser-based seating planner for teachers, built around a configurable hexagonal classroom.

## What teachers can do

- Create any course and give it a custom name.
- Paste or edit a student roster (one name per line, or comma-separated).
- Keep multiple courses and independent seating plans on one device.
- Configure rows, columns, and up to 60 desk spots.
- Drag students to desks and fine-tune desk positions.
- Place 4–8 shared A–H floor reference marks to help return desks to consistent positions.
- Print the current classroom map.
- Export and import JSON backups.

## Privacy

No student roster is embedded in this repository. Course names, student names, seating assignments, and room layouts are stored in the browser's local storage unless a teacher explicitly exports a JSON backup.

Exported backups contain student names and should be stored only in an approved, access-controlled location.

## Use

Open `index.html` in a modern browser. The application is self-contained and does not require a backend.

The classroom drawing is schematic. Always verify actual desk dimensions, accessible routes, walking space, and door clearance in the physical room.

## GitHub Pages

Because the application is a self-contained static page, it can be hosted with GitHub Pages from the repository root if desired.

Built for Tech-GLM classroom planning.
