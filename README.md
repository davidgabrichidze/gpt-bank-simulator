# GPT Bank Simulator

This repository contains an [Nx](https://nx.dev) monorepo with two applications:

- **web** – an Angular front‑end that simulates retail banking operations.
- **api** – a NestJS back‑end providing the API for the simulator.

## Development

Install dependencies and start the applications with Nx:

```bash
npm install
npx nx serve api    # start the NestJS API on http://localhost:3333
npx nx serve web    # start the Angular web app on http://localhost:4200
```

Both projects can be built and tested individually using the standard Nx commands, e.g. `npx nx build web`.
