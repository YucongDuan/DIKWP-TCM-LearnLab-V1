# DIKWP TCM LearnLab V1

A standalone, offline-first reference prototype for learning Traditional Chinese Medicine (TCM) through classics, terminology, four-examination data organization, synthetic pattern-reasoning cases, materia medica/formula safety, modern evidence, mentorship, and human assessment.

## Quick start
Open `index.html` in a modern browser. No server, database, model API, account, or network is required.

Optional CLI:
```bash
python run_demo.py examples/sample_learner.json --out outputs
```

## Core workflow
Learner profile → learning path → classics and terminology → synthetic four-examination case → candidate pattern reasoning → evidence and residuals → safety / red-flag gate → human assessment → Learning Passport.

## Medical boundary
This system does not diagnose real people, prescribe herbal medicines, provide doses, instruct self-needling, change medication, delay urgent care, or replace licensed clinicians, teachers, pharmacists, or medical institutions.

All cases are synthetic. Formula and herb cards are educational summaries without dosage or treatment instructions.

## Design lineage
This prototype extends the offline, evidence-ledger, human-review-first design principles of the DIKWP / Yucong Duan ecosystem, including `DIKWP-LearnPath-OS`, into TCM learning and supervised reasoning education.
