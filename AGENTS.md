# Showcase maintenance

This repository contains presentation material only. Preserve that scope.

- Maintain independently written product documentation, high-level diagrams, fictional examples, and reviewed screenshots of the actual interface.
- Keep application source, research prompts, scoring rules, internal schemas, datasets, evaluation results, raw web pages, logs, credentials, private audit reports, and operational configuration out of this repository.
- Never merge, rebase, cherry-pick, mirror, bundle, or import history from the private implementation repository. Updates arrive as reviewed file snapshots with independent public history.
- Use the private preparation workflow to capture screenshots and export an exact file allowlist. Do not recursively copy a development checkout or its Git directory.
- Use fictional business data and illustrative `example.com` links. Do not add real business imagery without documented publication rights. Review screenshots visually for identifying data and protected material; text scanners cannot inspect pixels.
- Keep `capture-manifest.json`, screenshot hashes, captions, viewport sizes, and coverage notes consistent. Never describe a component capture as an end-to-end app demonstration.
- Before release, run the private export validator and secret scanner on the exact proposed snapshot. Review all changes, including images. Agent instructions supplement these checks; they are not an access-control mechanism.
- Do not add deployment automation, credentials, private repository access, submodules, or executable workflows to this presentation without a separately reviewed scope change.
- Obtain owner approval before publishing new or changed material. Do not add a software license that grants rights to the private implementation.

## Code review rules

Flag any change that imports implementation details, private history, real research output, unreviewed media, or claims unsupported by the documented captures. Reject unexpected paths rather than assuming a file is safe because its filename looks harmless.
