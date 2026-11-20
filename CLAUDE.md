# HEAPY Edge

The site box that reads BAS points at a building. It is not opened from the BOG Toolkit hub, so it is a supporting repository under the standard. Repository `HEAPY-BOG/Heapy-edge`.

## The standard
This repository follows the HEAPY BOG module standard and branding guide. Read both before changing anything:
- https://github.com/HEAPY-BOG/BOG-Toolkit/blob/main/docs/standard/MODULE-STANDARD.md
- https://github.com/HEAPY-BOG/BOG-Toolkit/blob/main/docs/standard/MODULE-BRANDING.md

Check this repository against them with `python tools/check_module.py <this folder>` from a BOG-Toolkit clone.

## Quick reference
- **Runtime:** Node (see `package.json`).
- **Run:** `npm start`. **Tests:** `npm test` (`tests/selftest.js`). They must pass before you hand back work.
- **Version:** `version` in `package.json`. Raise it and add a `CHANGELOG.md` entry with every release.
- **Read only:** the box reads points. It writes nothing to a building system.

## Rules
- No client, project or person names in code, tests, sample data, docs or commit messages. Use Demo Community Hospital,
  DCH and Dayton OH.
- No key, token or password in the repository, in a log or in anything sent to a browser.
- Brand: palette tokens only, square corners, no shadows. Never write "heapy" in lowercase in text a person reads.
- BOGI is Building Optimization Group Intelligence: describe it by what it does, never as an AI.
- Commit to `main`; stage explicit paths.
- Ask Nick or Justin before you add a dependency, rename a setting, the key or a launcher, or change the package format.
