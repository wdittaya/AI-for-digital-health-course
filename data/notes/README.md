# Lab 8 test set

20 synthetic clinical notes (no real patients). For each note extract `age` (int), `sex` (M/F),
`conditions` (list of diagnoses) and `medications` (list of drug names). Submit a JSON object keyed by note id.
Metric: mean of age accuracy, sex accuracy, conditions F1 and medications F1 (synonyms such as HTN/hypertension are accepted).
