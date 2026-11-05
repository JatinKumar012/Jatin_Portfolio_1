# Jatin Kumar — Portfolio

A responsive personal engineering portfolio built with React, TypeScript, and Vite. It features a lazy-loaded React Three Fiber planet, reduced-motion support, scroll reveals, and a professional overview of Jatin's experience, skills, projects, and education.

## Development

```sh
npm install
npm run dev
```

## Validation

```sh
npm run lint
npm run build
```

## Personalize content

- Update portfolio copy, skills, project previews, and available profile links in `src/data/portfolio.ts`.
- Add individual repository or live-demo URLs there when they are available. The project cards intentionally do not invent URLs.
- Add a resume asset and link only when a current resume is ready.
- The contact form opens the visitor's default email app with the message prefilled; it does not send data to a service. Configure a backend or email provider before replacing this with an in-page send flow.
- The Pine Labs flow diagram is illustrative, not a depiction of a production system.
