# Lab 9 test set

`kb.json`: 40 synthetic guideline passages (teaching material, not clinical advice).
`questions.json`: 22 questions; some are NOT answerable from the knowledge base.
For each question submit the top-3 retrieved passage ids and your generated answer. Out-of-scope questions must be
answered with the phrase 'Not in the guidelines'. Metric: 0.5 * Recall@3 + 0.5 * abstention accuracy.
