# EMT-B Essentials

A focused EMT-Basic deck for the [NREMT cognitive exam](https://www.nremt.org/Handbooks/EMT/Cognitive-Exam),
authored for use with [Complement](https://complementai.app).

**231 atomic cards** following the AnKing-style standards in
[`decks/CARD_STANDARDS.md`](../CARD_STANDARDS.md). See
[`decks/DECK_AUTHORING_LEARNINGS.md`](../DECK_AUTHORING_LEARNINGS.md) for
process notes and common pitfalls.

## What's inside

Organized to match the current NREMT EMT cognitive exam content outline (Scene
Size-Up & Safety 15–19%, Primary Assessment 39–43%, Secondary Assessment 5–9%,
Patient Treatment & Transport 20–24%, Operations 10–14%).

| Subdeck | Cards | Coverage |
|---------|-------|----------|
| **Anatomy & Physiology** | 30 | directional terms, prefixes/suffixes, blood & air pathways, cardiac conduction, ANS, pulse points, skin layers, epi receptors |
| **Patient Assessment** | 21 | scene size-up, AVPU, XABCDE primary survey, SAMPLE, OPQRST, DCAP-BTLS, vital sign normals (adult/peds), GCS, reassessment intervals |
| **Airway & Ventilation** | 26 | OPA/NPA (indications/contraindications/sizing/insertion), suction rules, oxygen devices, BVM rates, distress vs failure vs arrest, lung-sound buzzwords, SpO₂ thresholds |
| **Cardiology & Resuscitation** | 24 | adult/peds CPR (rate, depth, ratio, hand position, recoil), AED priority + special cases, ACS sequence, atypical MI, CHF, cardiogenic shock |
| **Shock & Trauma** | 30 | four shock types, compensated vs decompensated, hemorrhage control, tourniquet rules, tension pneumothorax, flail chest, sucking chest wound, burns, spinal precautions |
| **Medical Emergencies** | 29 | Cincinnati stroke triad, seizure management, hypo vs hyperglycemia, anaphylaxis (definition/treatment/repeat-epi), opioid overdose triad + naloxone, OB (left tilt/crowning/prolapsed cord), poisoning routes |
| **Pharmacology** | 26 | EMT formulary; per-drug atomic cards for indication, dose, mechanism, contraindications across aspirin, nitro, epi, albuterol, oral glucose, activated charcoal, naloxone |
| **Pediatrics & Special Populations** | 25 | fontanelle clues (sunken/bulging/closure), peds airway differences, APGAR (acronym + per-component rubrics + buckets), infant pulse, geriatric atypical presentations |
| **Operations** | 20 | START triage colors + flow (RPM, cutoffs), hazmat zones (hot/warm/cold + staging), lifting body mechanics + move types, radio report structure |

Total: **231 cards** (up from a 73-card v1 after atomicity rework — see
`DECK_AUTHORING_LEARNINGS.md` for the rework process).

## Editing

Each note is a single Markdown file under `notes/<subdeck>/<slug>.md` with TOML
front-matter. The `id` field is a stable UUID — author it once and never
change it. See [Complement's spec](https://github.com/complement-ai/deck-starter)
for the full format.

## Sync to Complement

Push to `main` and Complement's webhook will diff and update the shared deck.

## Sources & references

- [NREMT EMT Cognitive Exam handbook](https://www.nremt.org/Handbooks/EMT/Cognitive-Exam)
- [NREMT EMT examination specifications (test plan)](https://www.nremt.org/admin/getmedia/4cb170ab-35fa-4ec0-a76c-634847005bc4/EMT-Test-Plan_Public)
- [2025 AHA CPR & ECC guidelines update](https://www.nremt.org/News/How-the-2025-AHA-Guidelines-Impact-National-Regist)

> NREMT examinations continue to use 2020 AHA guidelines while questions are
> reviewed and revalidated against the 2025 update (12–15 month transition).
> CPR cards in this deck use the 2020 numbers (rate 100–120/min, depth 2–2.4″,
> 30:2 single-rescuer adult) which remain operational.
