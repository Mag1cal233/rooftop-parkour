# English localisation

`zh-to-en.json` records the 65 original Chinese HUD strings and their English translations. `english-hud.patch` applies the translations and small text-spacing adjustments to `Source/Postcode/Route/RouteHUD.cpp` in the original Unreal project.

The patch also gives the rooftop route a readable English name in the records menu. It does not change route IDs, saved-record keys or movement rules.

This repository does not contain the complete Unreal project. The patch needs the existing project and its assets. The playable build is available under Releases.

The English package uses these settings in `Config/DefaultEngine.ini`:

```ini
[Internationalization]
Culture=en
Language=en
Locale=en-GB

[/Script/EngineSettings.GameMapsSettings]
GameDefaultMap=/Game/Maps/L_HA9_Rooftops
```

In `Config/DefaultGame.ini`, the package title is `Rooftop Parkour`, the internationalisation preset is `English`, and `en` is staged. The Windows Development build cooks `/Game/Maps/L_HA9_Rooftops` and its referenced assets. The original project and its existing builds were retained separately.

See the release's `validation.json` for the map fingerprint and checks performed on the packaged build.
