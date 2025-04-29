# Custom Note Service

A simple React app that allows users to add and view notes without a backend.

## Setup & Run

1. Clone the repository.
2. Run `npm install` to install dependencies.
3. Run `npm start` to start the development server.

## Why?

- **Storage Strategy**: Used `localStorage` because it's simple and persistent across sessions. Key `custom_notes` ensures namespacing.
- **State Management**: Used `useState` for simplicity and local state needs.
- **Styling**: Used plain CSS for clarity and control.
- **Navigation**: Used simple button-based navigation for minimalism.
- **Error/Loading States**: Spinner for saving feedback and alerts for errors ensure good UX.

## Deliverables

- URL of GitHub repo.
- Live site link (e.g., Vercel, Netlify).