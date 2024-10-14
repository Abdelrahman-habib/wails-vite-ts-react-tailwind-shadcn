# README

## About

A Wails template that comes with Vite, TypeScript, React, TailwindCSS and shadcn/ui.

### Using the Template

```console
wails init -n project-name -t https://github.com/Abdelrahman-habib/wails-vite-ts-react-tailwind-shadcn
```

```console
cd frontend
```

```console
npm install
```

### Installing Components

To install components, use shadcn's CLI tool to install

More info here: https://ui.shadcn.com/docs/cli#add

Example:

```console
npx shadcn-ui@latest add [component]
```

## Live Development

To run in live development mode, run `wails dev` in the project directory. In another terminal, go into the `frontend`
directory and run `npm run dev`. The frontend dev server will run on http://localhost:34115. Connect to this in your
browser and connect to your application.

## Building

To build a redistributable, production mode package, use `wails build`.
