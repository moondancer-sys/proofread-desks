# proofread-desks

Sealed proofread desks for the author's own reading, served by GitHub Pages (assignment-main AUTHOR_RULES F87,
DECISIONS D-557 item 9). Each page is encrypted with AES-256-GCM by `engine/proofread/seal.py` in
moondancer-sys/assignment-main; this repository holds ciphertext only. A page opens only from the full link whose
part after `#` is its key, and that key is never stored here or in any file.

| File | What it is | Original name |
|---|---|---|
| `INDEX.md` | this index | built here |
| `index.html` | landing page: says the desks open only from their full links | built here |
| `robots.txt` | asks every crawler to keep out | built here |
| `.nojekyll` | serves the files as they are | built here |
| `desks/2026-11-21_PNC520/DESK-PNC520-DECK_2026-11-21_SEALED.html` | sealed desk, PNC520 unit project deck, 27 slides | `DESK-PNC520-DECK_2026-11-21.html` |
| `desks/2026-11-21_PNC520/DESK-PNC520-BEDSIDE_2026-11-21_SEALED.html` | sealed desk, PNC520 bedside reference, 64 items | `DESK-PNC520-BEDSIDE_2026-11-21.html` |
| `desks/2026-11-21_PNC520/DESK-PNC520-EVALUATION_2026-11-21_SEALED.html` | sealed desk, PNC520 evaluation tools, 72 items | `DESK-PNC520-EVALUATION_2026-11-21.html` |
