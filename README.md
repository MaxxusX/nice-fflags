
# Nice FFlags

some nice little fflags i use
most of these are stolen from [luafv/rbxflags](https://github.com/luafv/rbxflags) and the [Bloxstrap Discord server](https://discord.gg/nKjV3mGq6R)

## Exclusive fullscreen

```json
{
  "FFlagHandleAltEnterFullscreenManually": "False"
}
```

## Enable ability to hide GUIs (if in maxxus's group)

| Key combination  | Action                                                                    |
| ---------------- | ------------------------------------------------------------------------- |
| Ctrl + Shift + B | Toggles GUIs in 3D space (BillboardGuis, SurfaceGuis, etc)                |
| Ctrl + Shift + C | Toggles game-defined ScreenGuis                                           |
| Ctrl + Shift + G | Toggles Roblox CoreGuis                                                   |
| Ctrl + Shift + N | Toggles player names, and other BillboardGuis that show up above a player |

```json
{
  "DFIntCanHideGuiGroupId": "5959518"
}
```

## Give maxxus the verified badge

```json
{
  "FStringWhitelistVerifiedUserId": "1056542255"
}
```

## Advanced graphics quality selector

```json
{
  "FFlagCommitToGraphicsQualityFix": "True",
  "FFlagFixGraphicsQuality": "True"
}
```

## Force `Future` lighting in all games

```json
{
  "FFlagDebugForceFutureIsBrightPhase3": "True"
}
```

## Preserve rendering quality with display scaling

```json
{
  "DFFlagDisableDPIScale": "True"
}
```

## Extend `Max Zoom Distance` in games with default zoom limits

```json
{
  "FIntCameraMaxZoomDistance": "2147483647"
}
```

## Disable full-screen titlebar

```json
{
  "FIntFullscreenTitleBarTriggerDelayMillis": "3600000"
}
```

## Disable captures keybind

```json
{
  "FFlagEnableCapturesHotkeyExperiment_v4": "False"
}
```

## Rename `Charts` to `Discover`

```json
{
  "FFlagLuaAppChartsPageRenameIXP": "False"
}
```

## Force Direct3D 11

```json
{
  "FFlagDebugGraphicsPreferD3D11": "True"
}
```

## Disable telemetry

```json
{
  "FFlagDebugDisableTelemetryEphemeralCounter": "True",
  "FFlagDebugDisableTelemetryEphemeralStat": "True",
  "FFlagDebugDisableTelemetryEventIngest": "True",
  "FFlagDebugDisableTelemetryPoint": "True",
  "FFlagDebugDisableTelemetryV2Counter": "True",
  "FFlagDebugDisableTelemetryV2Event": "True",
  "FFlagDebugDisableTelemetryV2Stat": "True"
}
```

## Disable In-Game Advertisements

```json
{
  "FFlagAdServiceEnabled": "False",
  "FFlagEnableAdsAPI": "False",
  "FStringImmersiveAdsUniverseWhitelist": "0",
  "FFlagImmersiveAdsWhitelistDisabled": "False"
}
```

## Custom Disconnect Message

```json
{
  "FFlagReconnectDisabled": "True",
  "FStringReconnectDisabledReason": "u got disconnected uwu"
}
```

## Hide `Beta` Badge

```json
{
  "FFlagVoiceBetaBadge": "False",
  "FFlagTopBarUseNewBadge": "False",
  "FFlagEnableBetaBadgeLearnMore": "False",
  "FFlagBetaBadgeLearnMoreLinkFormview": "False",
  "FFlagControlBetaBadgeWithGuac": "False",
  "FStringVoiceBetaBadgeLearnMoreLink": "null"
}
```
