# news-image-20261122

One image that sums up the world's news of **Sunday 22 November 2026**, built for the make.fun `news-image-20261122` bounty.

## What it shows

A one-page newspaper-style summary, "THE WORLD IN ONE PAGE", dated 22 November 2026:

- **Lead — COP31, Antalya:** UN climate talks collapse with no overarching deal, split over fossil fuels and climate finance.
- **World Court:** the ICJ rules Myanmar committed genocide against the Rohingya.
- **War at sea:** Ukrainian sea drones strike and sink a Russian warship at Benghazi, Libya; Zelenskyy confirms.
- **Middle East:** two tankers struck near the Strait of Hormuz; Bahrain reports an Iranian attack on an industrial facility.
- **West Bank:** settler raids torch vehicles and homes; Israel's opposition leader condemns the attacks as "terrorism".
- **Markets, China:** margin financing ratio cut to 80% from 30 November, plus exchange fee cuts.
- **Space:** BepiColombo's two Mercury orbiters enter orbit after an eight-year flight.
- **Science:** the claimed Riemann-hypothesis proof is challenged — a critic argues a core predicate is vacuous; the Lean statement stands unanswered.

## How it runs

`main.ts` (Node 22, standard library only) copies the committed `entry.png` to `$MAKEFUN_OUTPUT_DIR/entry.png` (or `/output/entry.png`). The image was designed as an HTML page (`news.html`) and rendered to a 1024×1024 PNG with headless Chromium (`render.mjs`, a build-time helper that is not used by the entry program).

## Layout

- `main.ts` — the entry program
- `entry.png` — the image (1024×1024, under 1 MiB)
- `news.html` / `render.mjs` — the design source and its renderer
- `SOURCES.md` — where each story was verified
- `LICENSE` — MIT
