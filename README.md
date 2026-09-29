# DeepFake Shield

React + Vite + TypeScript website for the multi-modal deepfake detection demo.

## Run in VS Code

1. Open this folder in VS Code.
2. Open Terminal → New Terminal.
3. Run:

```bash
npm install
npm run dev
```

4. Open the localhost URL shown by Vite.

## Build

```bash
npm run build
npm run preview
```

## GitHub Pages

The Vite base path is already configured for:

https://manmantesh815-maker.github.io/deepfake1/

The included GitHub Actions workflow builds the React app and deploys the `dist` folder.

Important: in the GitHub repository, remove or disable the old workflow that deploys the repository root (`static.yml`) so only the new build-and-deploy workflow is used.
