# Install

Openlands Native Edition installs through ECHO Launcher once approved release artifacts exist.

## Expected Flow

1. Launcher reads the alpha channel from `ECHO-Release-Index`.
2. Launcher resolves `openlands-native-edition`.
3. Launcher downloads the Native pack manifest.
4. Launcher expands `moduleRequirements`.
5. Launcher downloads `.echo-addon` artifacts from `ECHO-Modules`.
6. Launcher verifies SHA-256 checksums.
7. Launcher places artifacts in the Native runtime module directory.
8. Launcher starts `ECHO-Native-Platform` with the Openlands pack profile.

## Required Before Public Install

- `echoopenlandsprotocol-0.1.0.echo-addon` exists in a GitHub release.
- All required module artifacts are indexed with URL, size, and SHA-256.
- Native runtime can load `META-INF/echo.mod.json`.
- Openlands Standard config is selected by default.
- No Minecraft-derived assets are included.

