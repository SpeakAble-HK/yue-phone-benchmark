# yue-phone-benchmark (GH Pages demo)

Styled benchmark report + worst-clip audio demos.

- `benchmark.html` — the page (`index.html` redirects to it).
- `assets/` — 3 worst-clip WAVs (16 kHz mono).

Source of the report section: private `speakable-phone-benchmark`
(`scripts/build_benchmark_html.py` + `BENCHMARK.md`).
Regenerate: `python scripts/publish_styled_page.py --out <this-dir> --force`.
