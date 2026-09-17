# Contributing to the Brink bucket

**`brink.json` is generated, not authored.** The `release-brink` workflow in `getbrink/brink`
clones this repository on every CLI release and commits the new version, URLs and hashes. A hand
edit to the manifest is overwritten by the next release, so send the change to the workflow that
writes it.

## What a pull request here is for

- `README.md`: install instructions that do not match what a user actually experiences.
- A manifest field the release workflow does not manage.

## Testing a change

```powershell
scoop bucket add getbrink https://github.com/getbrink/scoop-bucket.git
scoop install getbrink/brink
brink version
```

Describe the version that ships: no compatibility or migration language, and no instructions for
releases that are no longer current.

## Reporting a bad hash

A URL or `hash` that does not match Brink's published artefact is a security report, not a pull
request. See `SECURITY.md`.

## Licence

By contributing you agree that your contribution is licensed under the Apache License 2.0 in
`LICENSE`.
