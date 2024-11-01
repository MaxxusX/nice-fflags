# Nice FFlags

some nice little fflags i use

## GUI Hiding

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

## Verify Maxxus

```json
{
  "FStringWhitelistVerifiedUserId": "1056542255"
}
```

<!-- TODO: apparently this no longer works. check later
## Advanced Graphics Quality Selector

```json
{
  "FFlagCommitToGraphicsQualityFix": "True",
  "FFlagFixGraphicsQuality": "True"
}
```
-->

## Force `Future` Lighting in All Games

```json
{
  "FFlagDebugForceFutureIsBrightPhase3": "True"
}
```

## Preserve Rendering Quality w/ Display Scaling

```json
{
  "DFFlagDisableDPIScale": "True"
}
```

## Extend `Max Zoom Distance` in Games With Default Zoom Limits

```json
{
  "FIntCameraMaxZoomDistance": "2147483647"
}
```

## Disable Fullscreen Titlebar

```json
{
  "FIntFullscreenTitleBarTriggerDelayMillis": "3600000"
}
```

## Disable `Captures` Keybind

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

## Disable Telemetry

```json
{
  "DFFlagClientBaseNetworkMetrics": "False",
  "DFFlagEnableLightstepReporting2": "False",
  "DFIntClientLightingTechnologyChangedTelemetryHundredthsPercent": "0",
  "DFIntCrashUploadToBacktracePercentage": "0",
  "DFIntLightstepHTTPTransportHundredthsPercent2": "0",
  "DFStringAltHttpPointsReporterUrl": "null",
  "DFStringAltTelegrafAddress": "0.0.0.0",
  "DFStringAltTelegrafHTTPTransportUrl": "null",
  "DFStringAnalyticsEventStreamUrlEndpoint": "null",
  "DFStringAnalyticsNS1BeaconConfig": "null",
  "DFStringCrashpadUploadToBacktraceAndroidPlayerToken": "null",
  "DFStringCrashUploadToBacktraceBaseUrl": "null",
  "DFStringCrashUploadToBacktraceMacPlayerToken": "null",
  "DFStringCrashUploadToBacktraceWindowsPlayerToken": "null",
  "DFStringHttpPointsReporterUrl": "null",
  "DFStringLightstepHTTPTransportUrlHost": "null",
  "DFStringLightstepHTTPTransportUrlPath": "null",
  "DFStringLightstepToken": "null",
  "DFStringRobloxAnalyticsURL": "null"
  "DFStringTelegrafAddress": "0.0.0.0",
  "DFStringTelegrafHTTPTransportUrl": "null",
  "DFStringTelemetryV2Url": "null",
  "FFlagDebugDisableTelemetryEphemeralCounter": "True",
  "FFlagDebugDisableTelemetryEphemeralStat": "True",
  "FFlagDebugDisableTelemetryEventIngest": "True",
  "FFlagDebugDisableTelemetryPoint": "True",
  "FFlagDebugDisableTelemetryV2Counter": "True",
  "FFlagDebugDisableTelemetryV2Event": "True",
  "FFlagDebugDisableTelemetryV2Stat": "True",
  "FStringCoreScriptBacktraceErrorUploadToken": "null",
  "FStringGamesUrlPath": "/games/",
  "GoogleAnalyticsAccountPropertyID": "null",
  "GoogleAnalyticsAccountPropertyIDPlayer": "null"
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

<!-- TODO: does this even exist anymore? -->
## Hide VC `Beta` Badge

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

### Remove auto translation sys message
> [!NOTE]
> `"Roblox automatically translates supported languages in chat."`

```json
{
  "FFlagChatTranslationEnableSystemMessage": "False"
}
```

### Increased Asset Preloading Count

```json
{
  "DFIntNumAssetsMaxToPreload": "10000",
  "DFIntAssetPreloading": "10000"
}
```

## Render Occlusion Culling
###### [@CloneTrooper1019](https://x.com/MaximumADHD/status/1832331711486865769)

```json
{
  "DFFlagUseVisBugChecks": "True",
  "FFlagEnableVisBugChecks27": "True",
  "FFlagVisBugChecksThreadYield": "True",
  "FIntEnableVisBugChecksHundredthPercent27": "100"
}
```
