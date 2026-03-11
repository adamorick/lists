# iOS Shortcuts

Use GitHub raw URLs to fetch the latest version of a list in Shortcuts.

## Raw URLs

- Gym Bag: `https://raw.githubusercontent.com/adamorick/lists/main/gym-bag.md`
- Context: `https://raw.githubusercontent.com/adamorick/lists/main/CONTEXT.md`

## Simplest Shortcut

1. Add a `URL` action with the raw GitHub URL for the file you want.
2. Add `Get Contents of URL`.
3. Add `Quick Look` or `Show Result`.

## One Shortcut For Multiple Lists

1. Add a `Choose from Menu` action.
2. Create one menu item per list.
3. In each menu branch, set the matching raw GitHub URL.
4. After the menu, use `Get Contents of URL`.
5. End with `Quick Look` or `Show Result`.

## Notes

- This is best for read access.
- Raw GitHub URLs return plain Markdown, which Shortcuts handles cleanly.
- If the repo is private, the shortcut will need authenticated GitHub access instead of unauthenticated raw URLs.
