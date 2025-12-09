# Ocean Notes – Astro Frontend

A simple, modern notes manager built with Astro following the Ocean Professional theme.

- Create, view, edit, and delete notes
- Notes are persisted to browser localStorage under the key `notes.v1`
- Sidebar lists your notes and highlights the selected one
- Main area shows the note title, last updated timestamp, and content
- Clean, rounded UI with subtle gradients and shadows

## Getting Started

Install dependencies and run the dev server:

```bash
npm install
npm run dev
```

Build and preview:

```bash
npm run build
npm run preview
```

The preview runs on port 3000 as configured.

## Usage

- Click “New” in the sidebar to create a note.
- Select a note in the sidebar to view it.
- Use “Edit” to modify the title/content; “Save” to persist.
- Use “Delete” to remove the selected note (confirmation shown).
- Notes are saved automatically in your browser and persist across reloads.

## Environment Variables (optional)

This UI is storage-adapter ready:
- PUBLIC_API_BASE or PUBLIC_BACKEND_URL: If set and a backend is added later, you can implement a remote adapter without changing the UI.
- No backend is required; the app works with an empty `.env`.

## Accessibility

- Buttons and list items are keyboard-accessible.
- Labels are associated with inputs.
- Visible focus styles on inputs.

## Theme

Ocean Professional palette:
- Primary: #2563EB
- Secondary: #F59E0B
- Error: #EF4444
- Background: #f9fafb
- Surface: #ffffff
- Text: #111827
- Gradient: soft blue to gray for depth

