# Firebase Chat Template

Look at the [Nuxt 3 documentation](https://nuxt.com/docs/getting-started/introduction) to learn more.

## Setup

Make sure to install the dependencies:

```bash
npm install
```

## Development Server

Start the development server on `http://localhost:3000`:

```bash
npm run dev
```

## Production

Build the application for production:

```bash
npm run build -- --preset=firebase
firebase deploy
```

Locally preview production build:

```bash
npm run build -- --preset=firebase
firebase emulators:start
```

Check out the [deployment documentation](https://nuxt.com/docs/getting-started/deployment) for more information.
