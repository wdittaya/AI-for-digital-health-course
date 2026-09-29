# Lab 10 test set

Diabetes 130-US hospitals (UCI id 296). The test set is a **patient-level** 20% hold-out: every encounter of a
held-out patient is in `test_ids.csv` (20352 encounters). Train on the remaining encounters only; never use
the `readmitted` column of test encounters. Target: readmitted within 30 days (`<30`). Submit `id,prob`. Metric: ROC AUC.
