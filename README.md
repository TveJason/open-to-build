# Open to Build

A modern, searchable front-end for [build-your-own-x](https://github.com/codecrafters-io/build-your-own-x).

## Features

- Automatically loads categories and tutorials from the upstream README on each visit.
- Search by title, technology, or language.
- Filter by programming language, including multi-language tutorials.
- Responsive category cards and direct tutorial links.
- Included README snapshot when live refresh is unavailable.

## Run locally

No build step or dependencies required. With Python installed:

```sh
python -m http.server 8000 --directory dist
```

Open http://localhost:8000. Serve `dist/` on any static web host.

## Source

`dist/index.html`, `style.css`, `app.js`, and `parser.js` implement the interface. `dist/README.md` is the upstream fallback snapshot.

## Attribution

Tutorial collection: CodeCrafters and the contributors to build-your-own-x, originally started by Daniel Stefanovic. Upstream collection is CC0; individual linked tutorials retain their own terms. This is an independent interface, not an official CodeCrafters product.
