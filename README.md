# Bel Air Collective

An event showcase for University of Maryland, College Park's Bel Air Hall and Arts Scholars community.

## Develop

Requires Node.js 20.19+ or 22.12+.

```sh
npm ci
npm run dev
```

## Production build

```sh
npm run build
npm run preview
```

Vite writes the deployable static website to `dist/`.

## Features

- Responsive Maryland red and gold design with community and Arts Scholars sections.
- Sample event cards, category filters, and text search.
- Event details and forms to create, edit, and delete events.
- Photo uploads up to 2 MB per photo.
- Events and uploaded photos persist in this browser's localStorage.

The initial events are examples. Edits are local to each browser and are not shared across devices or visitors. A shared event administration workflow requires a backend and authentication. Uploaded images consume browser storage; smaller images are recommended. Clearing browser site data removes saved edits.

Stock images load from Unsplash and fonts load from Google Fonts. No credentials are required. This is a community project, not an official university website.
