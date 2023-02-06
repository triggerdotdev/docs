# Trigger.dev Documentation

This repository contains the documentation for [Trigger.dev](https://trigger.dev).

### 👩‍💻 Development

If you wish to run this locally, follow the steps below.

Run these from the root of the repository

```
pnpm install
```

```
pnpm run dev
```

Go to http://localhost:3050

### 😎 Publishing Changes

Changes will be deployed to production automatically after pushing to the `main` branch.

You can also preview changes using PRs, which generates a preview link of the docs.

#### Troubleshooting

- Mintlify dev isn't running - Run `mintlify install` it'll re-install dependencies.
- Mintlify dev is updating really slowly - Run `mintlify clear` to clear the cache.
