# Inside the Mitochondrion

An interactive, browser-based 3D explainer of how mitochondria work, from a high-level overview down to the molecular machinery of the electron transport chain and ATP synthase.

Built for curious adults who half-remember biology from school. Drag to rotate, scroll to zoom, and step through five levels of detail.

## Run locally

It's a single static file, but it loads ES modules, so serve it over HTTP rather than opening the file directly:

```
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## Tech

A single `index.html` using [Three.js](https://threejs.org/) loaded from a CDN. No build step.
