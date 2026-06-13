# ECHO Openlands Native Edition

Openlands Native Edition is the ECHO Native Platform packaging lane for the Openlands official pack.

## Role

- Consumes `.echo-addon` artifacts from `ECHO-Modules`.
- Uses `echoopenlandsprotocol` as the canonical Openlands content source.
- Publishes Native install/update/rollback manifests for the ECHO Launcher.
- Does not own gameplay registries, balancing, names, textures, sounds, or recipes.

## Source Repos

- Protocol module: `knoxhack/ECHO-Modules/addons/echoopenlandsprotocol`
- Runtime: `knoxhack/ECHO-Native-Platform`
- SDK template: `knoxhack/ECHO-SDK/metadata/templates/openlands_official`
- Release index: `knoxhack/ECHO-Release-Index`

## Status

Implementation foundation only. Do not mark this edition public-ready until the Native artifact, install flow, update flow, repair flow, rollback flow, and parity tests pass.

## Preview Payload

- `preview-artifacts/echoopenlandsprotocol-0.1.0.echo-addon`
- `preview-artifacts/echoopenlandsprotocol-0.1.0-sources.jar`
- `manifests/modpack-index-entry.preview.json`

These files are checked in for repo visibility and handoff review only. They are not approved player-facing release artifacts.
