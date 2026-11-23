# Isometric Cloud Editor

An editor for cloud and network diagrams in isometric view, in the browser. Open the page, edit the example diagram
or its YAML text, and switch between the 3D drawing and a flat 2D board.

This repository holds only the built site, served by GitHub Pages. It is a static page: it makes no requests to
anything outside itself, keeps no analytics and sends nothing anywhere. It also works opened straight from a copy of
the folder (`index.html`).

## Using it

- **Select** a group, resource or connection on the drawing or in the tree; **F2** renames it (references follow),
  **⌘Z / Ctrl+Z** undoes.
- **3D | 2D** switches the view; the selection carries over.
- The diagram's text is a `cloud/1` YAML file; edits in the text and on the drawing stay in step.

The editor is MIT, built on `@johnoscott/isometric-engine` (MIT). Both licences, and the notices for the third-party
code the page bundles, are in `LICENSES.txt`.

## Disclaimer

Not affiliated with or endorsed by Amazon Web Services. AWS service names identify the services only; all shapes are
original drawings.
