<!-- SPDX-FileCopyrightText: 2026 Migiwa Project contributors -->
<!-- SPDX-License-Identifier: CC-BY-4.0 -->

# Publication Checklist

Before publishing the v0.1.0 release, consider replacing the placeholders below.

## Required edits

- `CITATION.cff`: replace `https://github.com/ty-mmh/migiwa` with the actual repository URL.
- `LICENSE`: replace `Migiwa Project contributors` if you want the copyright holder to be an individual, organization, or handle.
- `LICENSES/MIT.txt`: same copyright holder replacement if needed.

## Recommended release steps

```bash
git init
git add .
git commit -m "Release Migiwa v0.1.0"
git tag v0.1.0
```

After pushing to GitHub:

1. Create a GitHub Release for `v0.1.0`.
2. Archive the release with Zenodo if you want a DOI.
3. Save the repository snapshot to Software Heritage if you want an additional provenance anchor.
4. Add the DOI or archive URL back to `CITATION.cff` and the README in a follow-up commit.

## Release stance

Migiwa does not rely on scarcity. It relies on provenance.

The goal of v0.1.0 is to place the canonical source, terminology, and review lens into the world with a clear license and version history.
