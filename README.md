# saddle-legal

Public legal pages for the Spedora cycling training app, served by GitHub Pages:

- Privacy policy: `privacy/index.html` → https://ctfle.github.io/saddle-legal/privacy/
- Impressum: `imprint/index.html` → https://ctfle.github.io/saddle-legal/imprint/

The pages are generated in the app repo (ctfle/cycplan) from the same text the app shows
(`src/components/PrivacyPolicyContent.tsx`, `src/components/ImprintContent.tsx`) by
`npx vite-node scripts/buildLegalPages.ts`, which writes them to `docs/`. Change the text there
and copy the generated files here, so the app and these pages always say the same thing.

GitHub Pages: Settings → Pages → Deploy from a branch → `main`, `/ (root)`.
