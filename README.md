# Aggregate ledgers for lip and intra-oral place cues

Public companion to the manuscript “Lip and Intra-oral Cues for Place-of-Articulation Decoding in Pediatric Clinical Speech,” prepared for *Artificial Intelligence and Applications*.

These files are aggregate counts and summary scores for 895 clips and 51 speaker folds. They contain no video, no mouth-crop pixels, no speaker identifiers, and no source file names.

Identifiable recordings remain in hospital custody under approval No. 2024-EC-092 and are not in this repository.

## What each file supports

| File | Manuscript use |
|---|---|
| `ledgers/mouth_only_place_summary.json` | Mouth-only place accuracy, 50.36% |
| `ledgers/mouth_fusion_five_way_summary.json` | Mouth fused with audio, 56.97% |
| `ledgers/place_then_manner_summary.json` | Composed five-way accuracy, audiovisual place, and the locked true-place ceiling |
| `ledgers/place96_iteration1_summary.json` | Figure 3 count matrix and the first 96×96 row |
| `ledgers/place96_iteration2_summary.json` | Second 96×96 training |
| `ledgers/place96_layer_pooling_summary.json` | Layer-pooling 96×96 training |
| `ledgers/oracle_manner_blend_summary.json` | Diagnostic blend at a seen test weight, 88.59%. Not a deployable system |
| `ledgers/mouth_archive_status.json` | Crop size, frame rate, and clip count of the withheld feature archive |
| `figures/` | The three manuscript figures in PNG and draw.io |

The feature archive named inside the status file is not released. Fold-level prediction lists are not released.

## License

The aggregate ledgers and figures in this repository are released under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
