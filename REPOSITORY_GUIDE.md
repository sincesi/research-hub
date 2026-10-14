# Preparing a paper artifact

Use a dedicated repository per paper. Recommended structure:

```text
README.md
CHANGELOG.md
CITATION.cff
LICENSE
models/
diagnostics/
scripts/
results/
```

Create only the directories needed by that artifact. Existing artifacts may retain an established `validation/` layout. Select an appropriate license with the rights holders before publishing a license declaration. Confirm author names and order before adding citation metadata.

The README should identify the paper, separate original and corrected models, give exact execution commands and dependencies, and record expected results, bounds, and limitations. Do not commit credentials, private datasets, build caches, or unpublished manuscript files unintentionally.

Before a release, run its reproduction commands, record the environment and hashes, and update CHANGELOG. Connect that repository in Zenodo before publishing the release if automatic archival is intended. Confirm the resulting archive contains the correct files, then add its version DOI to the artifact README and this hub. Zenodo archival has not occurred merely because a GitHub commit exists.

References: [Zenodo repository integration](https://help.zenodo.org/docs/github/enable-repository/) and [release archival](https://help.zenodo.org/docs/github/archive-software/github-upload/).
