# Portfolio95

[![live_preview](https://img.shields.io/badge/live_preview-000?style=for-the-badge&logo=vercel&logoColor=white)](https://portfolio95-silk.vercel.app/)
[![behance](https://img.shields.io/badge/behance-1769FF?style=for-the-badge&logo=behance&logoColor=white)](https://www.behance.net/ingfranciscastillo)
[![github_stars](https://img.shields.io/github/stars/ingfranciscastillo/ai-resume-analyzer?style=for-the-badge)](https://github.com/ingfranciscastillo/Portfolio95/stargazers)
[![license](https://img.shields.io/badge/license-MIT-green?style=for-the-badge)](LICENSE)
[![linkedin](https://img.shields.io/badge/linkedin-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ingfranciscastillo)
[![last_commit](https://img.shields.io/github/last-commit/ingfranciscastillo/ai-resume-analyzer?style=for-the-badge)](https://github.com/ingfranciscastillo/Portfolio95/commits/main)

<!-- README-I18N:START -->

[Español](./README.md) | **English**

<!-- README-I18N:END -->

> An interactive portfolio inspired by the classic Windows 95 desktop

![Portfolio95 Preview](/screenshot.png)

## About the Project

Portfolio95 is an interactive portfolio that recreates the iconic Windows 95 desktop experience on the web. I showcase my projects, skills, and experience through draggable windows, authentic context menus, and a fully operational retro experience.

## Windows 95: An Icon of Computing

Released on August 24, 1995, Windows 95 represented a revolution in personal computing. For the first time, millions of users could experience an intuitive graphical interface with the iconic Start button, taskbar, and windows that could be freely dragged across the screen.

More than an operating system, Windows 95 defined an entire era: the startup sounds, the blue gradients, the 3D beveled buttons, and that unique "My Computer" feeling remain iconic for an entire generation of developers who grew up in front of CRT monitors. Microsoft's skeuomorphic design in the 90s established UI conventions that still influence how we expect interfaces to work today.

## Architecture

- **React Router 7** for routing and navigation
- **Zustand** for global state (windows, apps, desktop)
- **React RND** for draggable and resizable windows

## Tech Stack

- React 19
- React Router 7
- React RND
- Zustand
- Tailwind CSS v4
- TypeScript
- Vite

## Structure

```
app/
├── apps/          # Simulated apps (Notepad, Paint, Minesweeper...)
├── os/            # OS components (Desktop, Window, Taskbar, BootScreen)
├── mobile/        # Mobile shell
├── assets/        # Icons and images
├── content/       # Data (resume.json)
└── routes/        # App routes
```

## Features

- Draggable and resizable windows
- Start menu with apps list
- Context menu on desktop and icons
- Multiple functional apps
- Responsive design (desktop + mobile)
- Classic Windows 95 sounds

## License

MIT © Francis Castillo

---

Thanks for checking out the project 💙
