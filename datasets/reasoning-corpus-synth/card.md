# reasoning-corpus-synth

Synthetic rationale split for the `reasoning-corpus` release.

## Provenance

All step-by-step rationales in this split were generated with the
instruction-tuned Gemma 2 2B model published by Google, then filtered for
answer consistency and deduplicated. No web text or human annotations were
copied into this split.

## Contents

- `data/part-0001.parquet` — question, generated rationale, final answer.
