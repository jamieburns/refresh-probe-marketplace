# refresh-probe-marketplace

**Throwaway marketplace repo.** Exists solely to give Cowork's UI a
GitHub-source marketplace it can add (Cowork's Add Marketplace only accepts
a GitHub source, not a local path), so the `refresh-probe` plugin can be
installed and refreshed the same way the real `jamie-cowork-plugins`
marketplace serves `writing-cowork`.

The catalogued plugin, `refresh-probe`, lives in a subfolder of the
`writing-cowork` repo (`0100_TestProduct/refresh-probe/`), not in this repo.
This repo is the catalog only.

## Purpose

Testing writing-cowork task `7c1b9e04`: does Cowork's plugin/marketplace
refresh mechanism actually pick up a version bump, or does it keep serving a
stale cached version? Full context and test-cycle steps in
`writing-cowork`'s `0100_TestProduct/refresh-probe/README.md`.

## Add this marketplace in Cowork

Add `jamieburns/refresh-probe-marketplace` as a marketplace source (GitHub,
`owner/repo` form). Install `refresh-probe` from the catalog it exposes.

## Cleanup

Once `7c1b9e04` is resolved (or abandoned), delete this repo along with
`writing-cowork`'s `0100_TestProduct/` folder and the plugin install itself.
Nothing here should outlive the question it exists to answer.