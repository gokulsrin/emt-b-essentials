# EMT-B Essentials

A focused EMT-Basic deck for the [NREMT cognitive exam](https://www.nremt.org/Handbooks/EMT/Cognitive-Exam),
authored for use with [Complement](https://complementai.app).

**435 atomic cards** following the AnKing-style standards in
[`decks/CARD_STANDARDS.md`](../CARD_STANDARDS.md). See
[`decks/DECK_AUTHORING_LEARNINGS.md`](../DECK_AUTHORING_LEARNINGS.md) for
process notes and common pitfalls.

## What's inside

Organized to match the current NREMT EMT cognitive exam content outline (Scene
Size-Up & Safety 15–19%, Primary Assessment 39–43%, Secondary Assessment 5–9%,
Patient Treatment & Transport 20–24%, Operations 10–14%).

| Subdeck | Cards | Coverage |
|---------|-------|----------|
| **Anatomy & Physiology** | 52 | directional terms, prefixes/suffixes, blood & air pathways, cardiac conduction, ANS, pulse points, skin layers, epi receptors, body cavities/planes/quadrants, spine/long-bone/joint anatomy, GI/GU/endocrine systems, brain regions, coronary arteries, pleura/peritoneum, accessory muscles |
| **Patient Assessment** | 33 | scene size-up, general impression, trauma vs medical branching, AVPU, XABCDE primary survey, SAMPLE, OPQRST, DCAP-BTLS, rapid trauma assessment, focused exam, vital sign normals (adult/peds), GCS, pulse/respiratory/skin/pupil quality, BP cuff sizing, significant-MOI thresholds |
| **Airway & Ventilation** | 42 | OPA/NPA, suction rules, oxygen devices, BVM rates, E-C clamp + two-rescuer BVM, distress vs failure vs arrest, lung-sound buzzwords, SpO₂ thresholds, CPAP indications/contraindications, capnography (EtCO₂), agonal breathing, recovery position, head-tilt vs jaw-thrust, tripod positioning, cyanosis (central vs peripheral), pulse-ox limitations, FBAO recognition |
| **Cardiology & Resuscitation** | 36 | adult/peds CPR (rate, depth, ratio, hand position, recoil), AED priority + special cases, ACS sequence, atypical MI, CHF, cardiogenic shock, choking (adult/child/infant/unresponsive), post-ROSC priorities, irreversible signs of death, DNR field rules, shockable vs non-shockable rhythms, chain of survival, drowning resus |
| **Shock & Trauma** | 69 | four shock types + subtypes, compensated vs decompensated, Beck's triad, Cushing's triad, hemorrhage classes I–IV, hemorrhage control, tourniquet rules, tension pneumothorax, flail chest, sucking chest wound, abdominal evisceration, burns (rule-of-9s, electrical/chemical/inhalation, Parkland), pelvic binder, femur traction splint, fracture/dislocation/sprain, crush syndrome, compartment syndrome 6 P's, amputation handling, impaled object, eye injuries (globe/chemical/foreign body), dental avulsion, head trauma (epidural/subdural/concussion), SCI patterns (central/anterior/Brown-Séquard), neurogenic vs spinal shock, abdominal signs (Cullen's/Grey-Turner/Kehr's) |
| **Medical Emergencies** | 60 | Cincinnati stroke triad, seizure management, hypo vs hyperglycemia, anaphylaxis, opioid overdose, OB (delivery, prolapsed cord, fundal massage), poisoning routes, AAA, GI bleed (upper/lower), sepsis red flags, behavioral assessment + restraints, excited delirium, environmental (heat exhaustion vs stroke, hypothermia stages, frostbite, drowning, lightning, dive emergencies, snake/bee), pulmonary embolism, COPD exacerbation, DKA + Kussmaul, HHS, preeclampsia/eclampsia, ectopic, abortion, placenta previa vs abruption, postpartum hemorrhage, sickle cell crisis, dialysis missed, AEIOU-TIPS, TIA, ischemic vs hemorrhagic stroke, thrombolytic window |
| **Pharmacology** | 39 | EMT formulary; per-drug atomic cards for indication/dose/mechanism/contraindications (aspirin, nitro, epi, albuterol, oral glucose, activated charcoal, naloxone); 5 rights, 10 routes of administration, oxygen-as-drug, MDI technique, epi auto-injector technique, glucose tube safety, ALS-only formulary recognition, generic vs trade names, standing vs online medical control |
| **Pediatrics & Special Populations** | 52 | fontanelle clues, peds airway differences, APGAR (acronym + per-component + buckets + timing), infant pulse, geriatric atypical presentations, Pediatric Assessment Triangle (PAT — appearance/work-of-breathing/circulation, TICLS), croup vs epiglottitis vs bronchiolitis, febrile seizure, peds dehydration grading, SIDS, Broselow tape, newborn 30-second initial + resuscitation (3:1 ratio), meconium-stained fluid, premature infant, child abuse (TEN-4), elder abuse, special-needs (trach/G-tube/vent/autism), dementia vs delirium, bariatric transport, DNR/POLST/MOLST, peds trauma differences |
| **Operations** | 52 | START triage colors + flow, hazmat zones, lifting body mechanics + move types, radio report structure, ICS/NIMS/MCI command structure, JumpSTART peds triage, air-medical criteria + LZ + helicopter approach, refusal of care (AMA), expressed/implied/minor consent, mental-health hold, HIPAA basics, PCR + SOAP + CHART documentation, due regard / EVOC / intersection clearing / lights-and-sirens, ambulance staging, hazmat placards (DOT + NFPA 704), decontamination, PPE levels A–D, BSI, sharps disposal, exposure post-incident, crime scene preservation, active-shooter / rescue task force, daily ambulance check |

Total: **435 cards** (231 v2 atomic rework → 433 v3 NREMT-thorough expansion →
435 with abdominal evisceration and E-C clamp gap fills; see
`DECK_AUTHORING_LEARNINGS.md` for the multi-agent process).

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
