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
| `desks/2026-11-20_AL/DESK-AUG-CH1_2026-11-20_SEALED.html` | sealed desk, AL dissertation, Augustine chapter 1 | `DESK-AUG-CH1_2026-11-20.html` |
| `desks/2026-11-20_AL/DESK-AUG-CH2_2026-11-20_SEALED.html` | sealed desk, AL dissertation, Augustine chapter 2 | `DESK-AUG-CH2_2026-11-20.html` |
| `desks/2026-11-20_AL/DESK-AUG-CH3_2026-11-20_SEALED.html` | sealed desk, AL dissertation, Augustine chapter 3 | `DESK-AUG-CH3_2026-11-20.html` |
| `desks/2026-11-20_AL/DESK-AUG-CH4_2026-11-20_SEALED.html` | sealed desk, AL dissertation, Augustine chapter 4 | `DESK-AUG-CH4_2026-11-20.html` |
| `desks/2026-11-20_AL/DESK-AUG-CH5_2026-11-20_SEALED.html` | sealed desk, AL dissertation, Augustine chapter 5 | `DESK-AUG-CH5_2026-11-20.html` |
| `desks/2026-11-20_AL/DESK-FUN-CH1_2026-11-20_SEALED.html` | sealed desk, AL dissertation, Funny chapter 1 | `DESK-FUN-CH1_2026-11-20.html` |
| `desks/2026-11-20_AL/DESK-FUN-CH2_2026-11-20_SEALED.html` | sealed desk, AL dissertation, Funny chapter 2 | `DESK-FUN-CH2_2026-11-20.html` |
| `desks/2026-11-20_AL/DESK-FUN-CH3_2026-11-20_SEALED.html` | sealed desk, AL dissertation, Funny chapter 3 | `DESK-FUN-CH3_2026-11-20.html` |
| `desks/2026-11-20_AL/DESK-FUN-CH4_2026-11-20_SEALED.html` | sealed desk, AL dissertation, Funny chapter 4 | `DESK-FUN-CH4_2026-11-20.html` |
| `desks/2026-11-20_AL/DESK-FUN-CH5_2026-11-20_SEALED.html` | sealed desk, AL dissertation, Funny chapter 5 | `DESK-FUN-CH5_2026-11-20.html` |
| `desks/2026-11-21_RUBY/DESK-RUBY-PROPOSAL_2026-11-21_SEALED.html` | sealed desk, Proofread Desk RUBY_Portfolio_FINAL.docx | `DESK-RUBY-PROPOSAL_2026-11-21.html` |
| `desks/2026-11-21_HUBS/DESK-HUBS-PLAN_2026-11-21_SEALED.html` | sealed desk, Proofread Desk HUBS_Plan_FINAL.docx | `DESK-HUBS-PLAN_2026-11-21.html` |
| `desks/2026-11-24_AL-PPT/DESK-AIL-PPT_2026-11-24_SEALED.html` | sealed desk, Proofread Desk SOC332-Presentation_Chemeli_A-draft.pptx | `DESK-AIL-PPT_2026-11-24.html` |
| `desks/2026-11-24_AL-PPT/DESK-AUG-PPT_2026-11-24_SEALED.html` | sealed desk, Proofread Desk SOC332-Presentation_Chukwuemeka_A-draft.pptx | `DESK-AUG-PPT_2026-11-24.html` |
| `desks/2026-11-24_AL-PPT/DESK-FUN-PPT_2026-11-24_SEALED.html` | sealed desk, Proofread Desk SOC332-Presentation_Nyaucho_F-draft.pptx | `DESK-FUN-PPT_2026-11-24.html` |
| `desks/2026-11-24_AL-PPT/DESK-GRA-PPT_2026-11-24_SEALED.html` | sealed desk, Proofread Desk SOC332-Presentation_Njoroge_G-draft.pptx | `DESK-GRA-PPT_2026-11-24.html` |
| `desks/2026-11-25_AL-PPT/DESK-AIL-PPT_2026-11-25_SEALED.html` | sealed desk, Proofread Desk SOC332-Presentation_Chemeli_A-draft.pptx R26 | `DESK-AIL-PPT_2026-11-25.html` |
| `desks/2026-11-25_AL-PPT/DESK-FUN-PPT_2026-11-25_SEALED.html` | sealed desk, Proofread Desk SOC332-Presentation_Nyaucho_F-draft.pptx R27 | `DESK-FUN-PPT_2026-11-25.html` |
| `desks/2026-11-25_AL-PPT/DESK-GRA-PPT_2026-11-25_SEALED.html` | sealed desk, Proofread Desk SOC332-Presentation_Njoroge_G-draft.pptx R28 | `DESK-GRA-PPT_2026-11-25.html` |
| `desks/2026-11-25_AL-PPT/DESK-AUG-PPT_2026-11-25_SEALED.html` | sealed desk, Proofread Desk SOC332-Presentation_Chukwuemeka_A-draft.pptx R29 | `DESK-AUG-PPT_2026-11-25.html` |
