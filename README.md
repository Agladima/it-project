# TechNova Teams — HTML/CSS/JavaScript Demo

A front-end-only company collaboration workspace built with plain HTML, CSS, and JavaScript. It is designed as a demonstration project for a supervision exercise.

## Run it

1. Extract the folder if you downloaded the ZIP.
2. Open `index.html` in a modern browser, or use the VS Code **Live Server** extension.
3. Choose a demo account and click **Open demo workspace**.

No build tools or npm packages are required. Google Fonts are loaded from the internet; the app still works with system fonts if they are unavailable.

## Demo accounts

There are no passwords. Select an account on the welcome screen:

- Amara Okafor — Workspace Administrator
- David Mensah — IT Support Specialist
- Zainab Bello — Human Resources Officer
- Chidi Eze — Finance Associate
- Grace Williams — Marketing Coordinator

The `.example` email addresses and phone numbers are placeholders.

## Features

- Demo sign-in and sign-out by selecting a staff profile
- Company workspace navigation
- Chat list with All, Unread, and Groups filters
- Direct and group demo conversations
- Send messages, Enter-to-send, Shift+Enter for a new line, emoji button, copy message, and conversation details
- Teams and channels view
- Create teams and channels
- Staff directory with search and department filtering
- Add staff profiles and view staff profile details
- Start a direct chat from a staff profile
- Workspace search for staff and message text
- Responsive layout for desktop and mobile widths
- Local browser persistence using `localStorage`

## Important limitations

This is a simulation, not a Microsoft Teams integration. It does not create real Microsoft 365 accounts, send invitations, deliver messages to other users/devices, upload files, make calls, or store data on a server. Local changes are stored only in the current browser profile. For real multi-user access, the project would need a backend, authentication, database, and hosting.

## Reset demo data

In your browser's developer console, run:

```js
localStorage.removeItem('technovaTeamsDemo_v1');
location.reload();
```
