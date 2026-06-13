# Troubleshooting

## Pack Does Not Appear In Launcher

- Confirm Release Index includes `openlands-native-edition`.
- Confirm alpha launcher channel lists the Openlands Native catalog URL.
- Confirm validation is not `blocked`.

## Pack Fails To Launch

- Verify all `.echo-addon` artifacts exist and match SHA-256.
- Verify `echoopenlandsprotocol` contains `META-INF/echo.mod.json`.
- Verify ECHO Native Platform supports the declared module contracts.

## Gameplay Data Missing

- Check that `echoopenlandsprotocol` is installed.
- Check that block, item, recipe, biome, structure, creature, waystone, progression, tutorial, HoloMap, sound, and tag registries were loaded.

