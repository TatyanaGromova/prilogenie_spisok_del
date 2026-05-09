# Contributing Guide

Thanks for helping improve this project.

## Development Setup

1. Clone the repository.
2. Open `loving_diary_app_improved.html` in a browser.
3. Make changes in small, reviewable commits.

## Project Principles

- Keep app behavior stable unless change is intentional.
- Preserve existing `localStorage` keys and migration behavior.
- Prioritize mobile UX and readability.
- Respect `prefers-reduced-motion`.

## Code Style

- Use clear naming and keep functions focused.
- Avoid external JS libraries unless absolutely necessary.
- Keep UI language warm and consistent in Russian.
- When changing visuals, test both light and dark themes.

## Pull Request Checklist

- [ ] Change is scoped and documented.
- [ ] No regression in diary, mood, tasks, gratitude, win, history, theme toggle, and bottom nav.
- [ ] Habit scheduler behavior is verified.
- [ ] No obvious console errors.
- [ ] README/CHANGELOG updated when needed.
