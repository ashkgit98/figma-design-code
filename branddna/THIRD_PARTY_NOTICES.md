# Third-party notices

## bloub — circle bot face (Brad)

Brad's face engine (`src/components/brad/face/engine.ts`) is a TypeScript/React port of
the circle bot from **bloub** by Jérémy Perret: <https://github.com/jeremy-prt/bloub>
(commit `b4bb3c1`). Reused: the 16 rest expressions (values verbatim), the sphere-projected
capsule eyes, blink, gaze drift, pointer-follow and easeOutQuint morph logic. Adapted: colours
(face #111111, eyes #FFFFFF), blink cadence (3–6 s), morph duration (0.4 s), 2px idle float,
thinking scan, and the circle body only.

bloub's README notes it recreates the visual behaviour of the x.ai bot avatar and is not
affiliated with x.ai; its MIT licence covers the code, not the design it imitates.

Full licence text: `src/components/brad/face/LICENSE-bloub.txt`

```
MIT License

Copyright (c) 2026 Jérémy Perret

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
