# Update Flow

Native updates must be artifact-addressable.

## Policy

- Compare manifest module IDs, versions, sizes, and SHA-256 values.
- Download only missing or changed `.echo-addon` files.
- Preserve player saves, configs, screenshots, and local markers.
- Reject an update if `echoopenlandsprotocol` changes runtime IDs without a migration note.

## Openlands-Specific Checks

- Standard mode remains relaxed after update.
- Waystone state schema remains readable.
- HoloMap region IDs remain stable.
- Block/item IDs remain stable or ship a migration map.

