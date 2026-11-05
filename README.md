# Canvasmith Desktop

A desktop application shell prototype with project navigation, asset thumbnails, a central editing canvas and contextual property controls.

An ACRYL Blends blueprint for the **Desktop** category (`acrylblends.desktop-canvasmith`, category 63 of 100).

Status: designed, being built. `design/spec.md` is the specification and `design/mockup.html` the mockup (open it in a browser). The app itself,
composed from Cordis plugins (one `plugins/<feature>/` folder and one `blend.yaml` row per feature), lands here when it passes review.

When it is ready you will start it with:

```sh
npm create acrylblends@latest my-app -- --from acrylblends.desktop-canvasmith
cd my-app && npm install && npm run dev
```

Listed on https://acrylblends.github.io/blends and https://acryl.dev/blends.
