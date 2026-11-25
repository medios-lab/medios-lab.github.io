# medios-lab.github.io

The Medios landing page, served by GitHub Pages at https://medios-lab.github.io/.

- `index.html`: the page. Its copy button puts `Try Medios: https://medios-lab.github.io/try.txt` on the clipboard for the user to paste into a coding agent.
- `try.txt`: the entry text that agent follows. Generate it with `try/build-bundle` in medios-lab/medios, which writes `index.txt` next to the bundle tarball. Upload the tarball and its `.sha256` to the medios release the bundle's `release.json` pins, then replace `try.txt` with that `index.txt`. Never edit `try.txt` by hand: it carries the bundle's sha256.
- The docs at https://medios-lab.github.io/docs/ are published from medios-lab/docs.
