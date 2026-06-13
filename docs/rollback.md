# Rollback

Rollback returns the Native edition to the previous known-good manifest.

## Required Behavior

- Keep save data untouched.
- Restore previous module artifacts by checksum.
- Restore previous Openlands config overlay.
- Warn if the save was opened with a newer waystone, HoloMap, block, or item schema.

## Refuse Rollback When

- The previous manifest is missing.
- Required artifacts are unavailable.
- A save migration is irreversible and no compatibility shim exists.

