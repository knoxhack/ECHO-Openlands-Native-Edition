# Module Requirements

Openlands Native Edition consumes Native `.echo-addon` artifacts.

## Required

- `echocore`
- `echonetcore`
- `echoadaptercore`
- `echocontentcore`
- `echoworldcore`
- `echorecipecore`
- `echobiomecore`
- `echostructurecore`
- `echocreaturecore`
- `echofoundationcore`
- `echomaterialcore`
- `echotoolcore`
- `echostationcore`
- `echoworldstarter`
- `echocommonloot`
- `echocreatureroles`
- `echoprogressioncore`
- `echoassetcore`
- `echoopenlandsprotocol`

## Recommended

- `echoindex`
- `echotutorialcore`
- `echoholomap`
- `echosoundcore`
- `echoplayercore`
- `echorecovery`
- `echolootcore`
- `echoblockworks`
- `echoagriculturereclamation`
- `echonpcore`
- `echoeconomycore`

## Contract

The module graph must treat Echo IDs from `echoopenlandsprotocol` as the source of truth. Native implementation details cannot rename Openlands gameplay IDs.

## Runtime Evidence

Native builds must consume `data/echoopenlandsprotocol/openlands/systems/runtime_adapter_load_plan.json` and report every required adapter phase: `discover`, `load_data`, `register_content`, `bind_worldgen`, `bind_gameplay_state`, `ready`, and `release_gate`.

Before Public Alpha, the Native release manifest must include evidence for validator pass, uploaded artifacts with sha256, launcher install/update/repair/rollback, first-hour runtime playtest, waystone save/load, and legal content audit.

Native driver-surface implementation status must follow `data/echoopenlandsprotocol/openlands/systems/harness_driver_manifest_contract.json`; the current template lives at `evidence/native-harness-driver-manifest.template.json` and intentionally lists every real harness driver as missing.

The detailed evidence checklist lives in `docs/runtime-evidence.md`.
