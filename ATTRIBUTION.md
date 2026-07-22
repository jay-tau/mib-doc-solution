# Attribution

This repository is derived from Chris Strobl's public MIT-licensed
[`strobl/mib-doc-solution`](https://github.com/strobl/mib-doc-solution),
starting at commit `d6752ecd88220e8fcd07f6d6825d2b8d642c9edc` ("Merge score
improvements above 130"). Its Git history is preserved.

The upstream solution is itself based on 8090, Inc.'s MIT-licensed
[`8090-inc/mib-doc-challenge`](https://github.com/8090-inc/mib-doc-challenge).
The original 8090 copyright and MIT terms remain in [`LICENSE`](LICENSE).

This fork adds organizer-compatible runtime fixes and conservative
post-recovery adjudication safeguards. It does not copy another participant's
validation predictions.

Bundled OCR models and other third-party components retain their own notices,
provenance, checksums, and license texts in
[`third_party_licenses/`](third_party_licenses/README.md).
