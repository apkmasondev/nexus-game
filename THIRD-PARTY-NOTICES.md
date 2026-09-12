# Third-party notices

This file lists software that is redistributed as part of the published site in `dist/`,
together with the notices those licences require. It does not cover the project's own code
and assets; those are described in the Licensing section of `README.md`.

## Three.js

Rendering library. Bundled into the published JavaScript.

- Project: https://threejs.org — https://github.com/mrdoob/three.js
- Version: as pinned in `package.json` (`three`)
- Licence: MIT

```
The MIT License

Copyright © 2010-2025 three.js authors

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
```

## Draco 3D Data Compression — decoder

The geometry in `public/assets/*.glb` is Draco-compressed, so the published site serves
Google's decoder from `public/draco/`: `draco_decoder.wasm` and `draco_wasm_wrapper.js`.
Both files are copied unmodified from the installed Three.js distribution
(`node_modules/three/examples/jsm/libs/draco/gltf/`).

- Project: https://github.com/google/draco
- Copyright: The Draco Authors
- Licence: Apache License 2.0 — full text in [`licenses/Apache-2.0.txt`](licenses/Apache-2.0.txt)

The Apache licence requires that this notice and a copy of the licence travel with the
distributed files. Keep `licenses/Apache-2.0.txt` and this section in any deployment that
serves `public/draco/`.

## Vite

Build tool. Used to produce `dist/`; no Vite code is shipped to the browser.

- Project: https://vite.dev — https://github.com/vitejs/vite
- Version: as pinned in `package.json` (`vite`, dev dependency)
- Licence: MIT
