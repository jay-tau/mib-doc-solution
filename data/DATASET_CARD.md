---
license: mit
pretty_name: MIB Doc Challenge Data
task_categories:
- image-to-text
- text-classification
language:
- en
tags:
- document-processing
- ocr
- synthetic
size_categories:
- 1K<n<10K
---

# MIB Doc Challenge Data

Synthetic PDF packets for 8090's MIB Doc Challenge: Intergalactic Intake. Participants extract structured fields from messy, adversarial document packets and classify each case as `APPROVED`, `DENIED`, or `NEEDS_REVIEW`.

## Contents

The versioned archive `mib-doc-challenge-public-data-v2026-07-07.zip` contains:

- `data/train/`: 1,000 training PDFs
- `data/train_labels.csv`: public labels for the training PDFs
- `data/validation/`: 5,000 unlabeled validation PDFs
- `data/validation_manifest.csv`: validation case IDs, paths, and page counts

Validation answers and the final private test set are not included.

## Integrity

SHA-256:

```text
a9bb8c1bbf51346ebf49c2e3e1acdb7a5d6cd0760162767b0d133c7b7200f3c4  mib-doc-challenge-public-data-v2026-07-07.zip
```

## Data characteristics

All applicant identities, documents, portraits, and case records are synthetic. The PDFs intentionally include scan degradation, conflicting evidence, hidden text, fake answer keys, and other adversarial content. Hidden instructions are part of the challenge and are not trustworthy labels.

## Usage

Use this dataset with the public challenge repository at <https://github.com/8090-inc/mib-doc-challenge>. The repository contains the field manual, schemas, evaluator, submission validator, and Docker runtime contract.

## License

Released under the MIT License.
