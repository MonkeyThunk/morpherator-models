# coreml-2026-10-29: Core ML models for Morpherator

Core ML packages converted from Demucs (htdemucs, htdemucs_6s: stem separation) and all-in-one (the 8
harmonix folds: beats, downbeats, song parts). Each package is published as its files (a release holds no
folders): an asset named `<package>__<path>` belongs at `<package>/<path>`. `coreml-models.json` lists every
file with its size and SHA-256, and `SHA256SUMS` checks the whole release.

| Package | Precision | Bytes | Licences |
|---|---|---|---|
| `allin1-harmonix-fp32.mlpackage` | fp32 | 27,283,857 | LICENSE-all-in-one.txt, LICENSE-coreml-conversion.txt |
| `htdemucs-fp16.mlpackage` | fp16 | 105,215,844 | LICENSE-demucs.txt, LICENSE-coreml-conversion.txt |
| `htdemucs-fp32.mlpackage` | fp32 | 209,711,136 | LICENSE-demucs.txt, LICENSE-coreml-conversion.txt |
| `htdemucs_6s-fp16.mlpackage` | fp16 | 75,037,963 | LICENSE-demucs.txt, LICENSE-coreml-conversion.txt |
| `htdemucs_6s-fp32.mlpackage` | fp32 | 149,362,642 | LICENSE-demucs.txt, LICENSE-coreml-conversion.txt |

## Licences
MIT throughout. The weights keep their upstream notices: Demucs, Copyright (c) Meta Platforms, Inc. and
affiliates (`LICENSE-demucs.txt`); all-in-one, Copyright (c) 2023 Taejun Kim (`LICENSE-all-in-one.txt`). The
Core ML conversion is Copyright (c) 2026 MonkeyThunk (`LICENSE-coreml-conversion.txt`). Whoever reuses a
package keeps both notices with it.
