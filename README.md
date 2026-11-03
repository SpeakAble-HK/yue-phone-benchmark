# yue-phone-benchmark (GH Pages demo)

Static demo page for the 50-clip Cantonese phone benchmark.

- `BENCHMARK.html` — the page (`index.html` redirects to it).
- `assets/` — 3 worst-clip WAVs (16 kHz mono, vendored from the private benchmark).

Regenerate: `python scripts/build_demo_page.py --out <this-dir> --force`
(needs `/tmp/opencode/detail/*.json` from `/v1/phoneme/detail`; see script header).

Publish: `gh repo create SpeakAble-HK/yue-phone-benchmark --private --source=. --push`, then Settings → Pages → Deploy from branch → `main`.
