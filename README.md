# Planboard AI — AI-Powered Project Tracker & Infinite Whiteboard

A high-performance project tracker and visual whiteboard powered by Gemini AI, combining Kanban-style task management, vector drawing tools, sticky notes, Pomodoro focus sessions, and AI-assisted work reports in an interactive infinite-canvas workspace.

[![pnpm](https://img.shields.io/badge/pnpm-12.15.0-F69220?style=for-the-badge&logo=pnpm&logoColor=white)](https://pnpm.io/)
[![Next.js](https://img.shields.io/badge/Next.js-App_Router-black?style=for-the-badge&logo=next.js&logoColor=white)](https://nextjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-Type_Safe-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-v4-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)
[![Gemini AI](https://img.shields.io/badge/Gemini_AI-Powered-4285F4?style=for-the-badge&logo=googlegemini&logoColor=white)](https://ai.google.dev/)

<p align="center">
  <img width="49%" alt="Photocard Studio screenshot 2" src="https://github.com/user-attachments/assets/670146da-12d7-4a0c-b30b-6bac9df65212" />
  <img width="49%" alt="Photocard Studio screenshot 1" src="https://github.com/user-attachments/assets/9858c264-c483-48c3-9b49-1aecda5358cc" />
</p>



## Table of Contents

- [About](#about)
- [Features](#features)
  - [Infinite Canvas Board](#infinite-canvas-board)
  - [Interactive Project Cards](#interactive-project-cards)
  - [Drawing Whiteboard](#drawing-whiteboard)
  - [Pomodoro Focus Timer](#pomodoro-focus-timer)
  - [Universal Parent Navigator](#universal-parent-navigator)
  - [Today Focus Panel](#today-focus-panel)
  - [Quick Inbox](#quick-inbox)
  - [AI-Powered Work Reports](#ai-powered-work-reports)
  - [Canvas Navigation Controls](#canvas-navigation-controls)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## About

Planboard AI is a visual project management and productivity workspace built around an interactive infinite canvas. It combines structured task tracking with freeform visual planning, allowing users to organize projects, sketch ideas, connect related concepts, and monitor their progress in one place.

With interactive project cards, vector drawing tools, color-coded sticky notes, and a floating Pomodoro timer, Planboard AI brings task management and visual thinking together. Its Gemini-powered reporting tools also help turn ongoing project activity into polished daily status updates that are easier to review and share.

## Features

### Infinite Canvas Board

- **Infinite Canvas:** Navigate a spacious, responsive dot-grid workspace designed for visual project planning.
- **Smooth Panning:** Move around the canvas using middle-click or Space + drag.
- **Zoom Controls:** Zoom in and out using Ctrl + Scroll.
- **Horizontal Panning:** Navigate laterally using Alt + Scroll.
- **Flexible Workspace:** Arrange project cards, drawings, annotations, and sticky notes across the canvas.

### Interactive Project Cards

- **Editable Project Cards:** Double-click a card to edit its title and description.
- **Status-Based Filtering:** Filter cards using the `All`, `Todo`, `Doing`, and `Done` status tabs.
- **Progress Indicators:** Monitor project status and task completion.
- **Task Management:** Add, reorder, edit, and check off tasks using drag-and-drop interactions.
- **Dates and Priorities:** Assign dates and priority tags to organize work.
- **Blocker Tracking:** Keep track of issues that may prevent tasks from progressing.
- **External Links:** Bookmark relevant links directly within project cards.
- **Collapsible Cards:** Minimize cards to reduce clutter on the canvas.

### Drawing Whiteboard

- **Vector Pen:** Draw freeform sketches with customizable stroke colors, widths, and opacity.
- **Shape Tools:** Draw rectangles, ellipses, and directional arrows with customizable fills.
- **Interactive Resizing:** Resize selected rectangles and ellipses using draggable corner handles.
- **Smart Connection Arrows:** Keep arrow endpoints aligned with shape borders as connected shapes are resized.
- **Text Blocks:** Add text annotations directly to the canvas.
- **Color-Coded Sticky Notes:** Create, move, and organize sticky notes using drag-and-drop interactions.
- **Drawing Manipulation:** Select, move, resize, and delete vector drawings.

### Pomodoro Focus Timer

- **Floating Timer Card:** Open a floating timer that continues running in the background.
- **Dynamic Island-Style Widget:** Collapse the running timer into a compact `220px × 56px` pill displaying time progress and quick pause controls.
- **Audio Feedback:** Play subtle tick and click sounds during interactions, with a completion arpeggio when a session ends.
- **Quick Mute:** Toggle sound feedback when needed.
- **Customizable Durations:** Adjust Focus, Short Break, and Long Break intervals using increment and decrement controls.

### Universal Parent Navigator

- **Flexible Navigation:** Use a reusable navigation component designed for accessible, consistent navigation.
- **Visual Variants:** Support `filled`, `outline`, and `plain` styling variants.
- **Customizable Appearance:** Configure border separators, SVG outline and fill mappings, and dynamic sizing.

### Today Focus Panel

- **Priority Task Pinning:** Pin up to three priority tasks from different project cards.
- **Focused Workflow:** Keep the most important tasks visible without having to navigate between multiple cards.

### Quick Inbox

- **Quick Idea Capture:** Record ideas and tasks as they come to mind.
- **Task Promotion:** Move captured ideas into project cards when they are ready to be organized.

### AI-Powered Work Reports

- **Automated Daily Reports:** Compile daily status updates from active project cards.
- **Spelling and Grammar Refinement:** Polish report text for clarity and readability.
- **Multiple Writing Tones:** Rewrite reports in four styles:
  - **Concise:** Short, direct status updates.
  - **Professional:** Polished workplace communication.
  - **Bullets:** Structured updates that are easy to scan.
  - **Executive:** Summaries tailored to high-level progress reporting.
- **Batch Export:** Export and download generated report files together.

### Canvas Navigation Controls

| Action | Control |
| --- | --- |
| Pan the canvas | Middle-click or Space + drag |
| Zoom the canvas | Ctrl + Scroll |
| Pan horizontally | Alt + Scroll |
| Edit a project card | Double-click the card |

## Tech Stack

- **Package Manager:** [pnpm](https://pnpm.io/) v12.15.0 — Project dependency management.
- **Framework:** [Next.js](https://nextjs.org/) — App Router and Turbopack.
- **Runtime:** [Node.js](https://nodejs.org/) — JavaScript runtime for development and production.
- **Styling:** [Vanilla CSS](https://developer.mozilla.org/en-US/docs/Web/CSS) and [Tailwind CSS](https://tailwindcss.com/) — Custom styling and utility-based layouts.
- **State Management & Storage:** Client-side reactive state synchronized with browser `localStorage`.
- **AI Integration:** [Gemini AI](https://ai.google.dev/) — AI-assisted work report generation and text refinement.
- **Architecture:** Feature-oriented modules separating drawing tools, project management, shared components, and utilities.
- **Type Definitions:** TypeScript declaration files for shared application types.

## Getting Started

### Prerequisites

Make sure you have the following installed:

- **Node.js:** A version compatible with the Next.js version used by the project.
- **pnpm:** Version `12.15.0`, as specified by the project.

### Installation

**1. Clone the repository**

Use your repository URL to clone the project:

```bash
git clone https://github.com/AbdullahAlMaksud/planboard-web.git
cd planboard-web
```

**2. Install dependencies**

```bash
pnpm install
```

**3. Configure environment variables (If Needed)**

Create a `.env.local` file in the project root and configure the required variables using `.env.example` as your reference, if your local setup requires it.

See [Environment Variables](#environment-variables) for details.

**4. Start the development server**

```bash
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.


### Environment Variables

Planboard AI uses Gemini AI to generate and refine work reports. The supplied project description does not specify the exact environment variable names or API credential setup.

If the Gemini integration requires an API key:

1. Check the application's configuration for the expected environment variable name.
2. Add the required value to a local `.env.local` file if supported by the application.
3. Keep API credentials private and never commit secrets to the repository.

The core project workspace is described as using browser `localStorage` for client-side state persistence.

### Available Scripts

| Command | Description |
| --- | --- |
| `pnpm dev` | Start the Next.js development server. |
| `pnpm build` | Create an optimized production build. |
| `pnpm start` | Run the production build. |

### Project Structure

Planboard AI follows a feature-oriented project structure that separates the main application, reusable UI components, shared utilities, and core project-management and drawing features.

```text
planboard/
├── public/                     # Static public assets
└── src/
    ├── app/                    # Next.js App Router pages and layouts
    ├── components/
    │   ├── ui/                 # Reusable UI primitives
    │   └── common/             # Shared layout components
    ├── shared/
    │   ├── lib/                # Storage, seed data, and utilities
    │   └── types/              # Shared TypeScript declarations
    └── features/               # Core application features
        ├── draw/                # Whiteboard tools and drawing components
        └── project/             # Project cards, tasks, dialogs, and reports
```

### Deployment

Bonton can be deployed to [Vercel](https://vercel.com/) or another hosting platform that supports Next.js.

Before deploying, configure the environment variables required by your chosen storage integrations and ensure that the database and GitHub API settings are correct.

To build and run the production application:

```bash
pnpm build
pnpm start
```

For platform-specific instructions, consult the [Next.js deployment documentation](https://nextjs.org/docs/app/getting-started/deploying).

## Contributing

Contributions, bug reports, and feature suggestions are welcome.

1. Fork the repository.
2. Create a feature branch:

   ```bash
   git checkout -b feature/amazing-feature
   ```

3. Commit your changes:

   ```bash
   git commit -m "feat: add amazing feature"
   ```

4. Push the branch:

   ```bash
   git push origin feature/amazing-feature
   ```

5. Open a pull request.

For larger changes, consider opening an issue first to discuss the proposed improvements.

## License

Distributed under the **MIT License**. See [`LICENSE`](./LICENSE) for details.

## Contact

**Abdullah Al Maksud**

- **Email:** [maksud.workspace@gmail.com](mailto:maksud.workspace@gmail.com)
- **Website:** [abdullahalmaksud.com](https://abdullahalmaksud.com)
- **LinkedIn:** [@AbdullahAlMaksud](https://linkedin.com/in/AbdullahAlMaksud)
- **GitHub:** [@AbdullahAlMaksud](https://github.com/AbdullahAlMaksud)
