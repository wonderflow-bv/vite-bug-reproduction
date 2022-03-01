# Vite bug reproduction

This is a problably Vite related issue reproduction. We are still investaging if the issue is because of Vite or because of our code.

You can follow the discussion on [Github](https://github.com/wonderflow-bv/wanda/discussions/86)

The minimum viable npm version you can use is one that supports workspaces (7+)

To test this repro:

- `npm i`
- `cd apps/app && npm run dev -- --force` (use --force so that Vite rebuild cached dependencies)
- `cd apps/app-ds && npm run dev -- --force`
