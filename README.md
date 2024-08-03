<h1 align="center">setfflag</h1>

#### Version: `setfflag`
* **SynZ & Wave**

<h3 align="center">꧖ꦿꦸ</h3>

<h1 align="center">Lightning Technologies</h1>

### Voxel Lighting (Phase 1)
```

setfflag("DebugRenderForceTechnologyVoxel", "True")

```
### Future Lighting (Phase 3)
```

setfflag("FFlagDebugForceFutureIsBrightPhase3", "True")

```

<h1 align="center">Graphical Settings</h1>

### Disable Shadows
```

setfflag("CullFactorPixelThresholdShadowMapHighQuality", "2147483647")
setfflag("CullFactorPixelThresholdShadowMapLowQuality", "2147483647")

```
### Preserve rendering quality with display setting
```

setfflag("DisableDPIScale", "True")

```
### Low Graphics Quality w/ Max Render Distance/FRM Quality Levels
###### Explanation: 1-6 Are low graphics, Above 6 are high graphics. Like the 1-21 graphics slider
```

setfflag("DebugFRMQualityLevelOverride", "1")

```
### Low Render Distance
###### [FRM](https://github.com/luafv/rbxflags/tree/master?tab=readme-ov-file#frm-levels)
```

setfflag("DebugRestrictGCDistance", "1")

```
### Makes avatars shiny 
###### [everything goes black on <3] ***[DebugFRMQualityLevelOverride is there to set your graphics to 10, You can change it to anything above 3: [Click here to view](https://github.com/luafv/rbxflags/tree/master?tab=readme-ov-file#frm-levels) ]***
```

setfflag("RenderClampRoughnessMax", "-640000000")
setfflag("DebugFRMQualityLevelOverride", "6")

```
### Pause Voxelizer/Disable Baked Shadows
```

setfflag("DebugPauseVoxelizer", "True")

```
### Force LOD on Meshes
```

setfflag("CSGLevelOfDetailSwitchingDistance", "0")
setfflag("CSGLevelOfDetailSwitchingDistanceL12", "0")
setfflag("CSGLevelOfDetailSwitchingDistanceL23", "0")
setfflag("CSGLevelOfDetailSwitchingDistanceL34", "0")

```
### High Quality Textures 
###### *[1-3]*
```

setfflag("TextureQualityOverrideEnabled", "True")
setfflag("TextureQualityOverride", "3")

```
### Lower Quality Textures 
###### *[1-3]*
```

setfflag("PerformanceControlTextureQualityBestUtility", "-1")

```
### No avatar textures
```

setfflag("TextureCompositorActiveJobs", "0")

```

<h1 align="center">Quality of Life</h1>

### FPS Unlocker
```

setfflag("TaskSchedulerTargetFps", "9999")

```
### GUI Hiding Toggles
```

setfflag("FFlagUserShowGuiHideToggles", "True")
setfflag("GuiHidingApiSupport2", "True")

```
### Hide guis
###### ***Instructions: Replace "ID" with any group ID that you are in.***
| Key combination   | Action                                                                    |
| ----------------- | ------------------------------------------------------------------------- |
| Ctrl + Shift + B  | Toggles GUIs in 3D space (BillboardGuis, SurfaceGuis, etc)                |
| Ctrl + Shift + C  | Toggles game-defined ScreenGuis                                           |
| Ctrl + Shift + G  | Toggles Roblox CoreGuis                                                   |
| Ctrl + Shift + N  | Toggles player names, and other BillboardGuis that show up above a player |
```

setfflag("CanHideGuiGroupId", "ID"

```
### MTU 
```

setfflag("ConnectionMTUSize", "MTU_HERE")

```
### No Internet Disconnect 
###### *[You will still be kicked but the message wont show.]*
```

setfflag("DebugDisableTimeoutDisconnect", "True")

```
### Adjust Default Timeout Time
###### 1 second = 1000
###### @dis_spencer
```

setfflag("DefaultTimeoutTimeMs", "10000")

```
### Disable In-Game Purchases
```

setfflag("Order66", "True")

```
### Disable Dynamic Heads Animations
###### https://roblox.fandom.com/wiki/Dynamic_Head
```

setfflag("AnimationLodFacsDistanceMin", "0")
setfflag("AnimationLodFacsDistanceMax", "0")
setfflag("AnimationLodFacsVisibilityDenominator", "0")

```

<h1 align="center">User Interface/Visuals</h1>

### Custom MicroProfile Scale
```

setfflag("MicroProfilerDpiScaleOverride":  "100")

```

<h1 align="center">Audio Related</h1>

### Allows you to change voice chat distance 
###### default: [Min 7 Max 80]
```

setfflag("VoiceChatRollOffMinDistance", "7")
setfflag("VoiceChatRollOffMaxDistance", "80")

```
### Limit audios that are being played
```

setfflag("MaxLoadableAudioChannelCount", "1")

```
### Mess with voice chat volume
###### default 1000
```

setfflag("VoiceChatVolumeThousandths", "100000")

```

<h1 align="center">Physics (Abusive)</h1>

### Tool Desync
```

setfflag("SimBlockLargeLocalToolWeldManipulationsThreshold", "-1")

```
### Weird Leg Movement
```

setfflag("AnimatorPostProcessIK", "True")

```
### Adjust Hip Height Clamps
###### https://www.roblox.com/bundles/63/Mage-Animation-Package
```

setfflag("HipHeightClamp", "-48")

```
### Random High Jumps
###### https://youtu.be/2JkA4hWCAWw
```

setfflag("SimHumanoidTimestepModelUpdate", "True")

```
### Drunk
```

setfflag("SimAdaptiveHumanoidPDControllerSubstepMultiplier", "-999999")
setfflag("SimHumanoidTimestepModelUpdate", "True")

```
### No Animations
###### **Stops the game from trying to replicate your animations in the server. You dont have animations in the server but you do for your client**
```

setfflag("ReplicatorAnimationTrackLimitPerAnimator", "-1")

```
### Stick unanchored parts to you
##### - = up, + = down
```

setfflag("SolidFloorPercentForceApplication", "-1000")
setfflag("NonSolidFloorPercentForceApplication", "-5000")

```
### Max Raycast Distance
###### Raycasting is the use of intersection tests to solve problems in ROBLOX. The most common use of raycasting is to determine the first object intersected by a ray. This is done by casting a virtual ray from a certain point in a direction and determining the first surface it intersected with.
###### Break legs collision from 2 to -inf, kinda break camera on values over 3 noclip cam on 3
```

setfflag("RaycastMaxDistance", "3")

```
### Possible Super Jump
```

setfflag("NewRunningBaseGravityReductionFactorHundredth", "1500")

```
### Change DataSender Rate
###### a.k.a does not let you load games
```

setfflag("DataSenderRate", "-1")

```
### Disable Touch Events
```

setfflag("TouchSenderMaxBandwidthBps", "-1")

```
### Fake Lag
```

setfflag("S2PhysicsSenderRate", "1")

```
### Invisible 1
###### **Stops the physics on your character froms sending to the server so your character doesn't move for the server. You can move on your client.**
```

setfflag("S2PhysicsSenderRate", "-30")

```
### Invisible 2
###### Locks your character's position on the server to (0, 0, 0), having the side effect of turning you invisible. This only affects the server and other clients, not you. server-sided things that rely on your position, like clicking to get tools, will not function. In some games these can be abusable. Here is a list of them: [Link](https://docs.google.com/document/d/1_kQr-tkc97lcg7ZvFfJdt8UzaziIfwuJPrzR6sTOLHo/)
```

setfflag("GameNetPVHeaderTranslationZeroCutoffExponent", "10")

```
### Invisible 3
###### Restricts the client from sending any physics-related information. This means other people can topple you over.
```

setfflag("PhysicsSenderMaxBandwidthBps", "1")
setfflag("PhysicsSenderMaxBandwidthBpsScaling", "0")

```
### Warp & Slowmotion
```

setfflag("MaxMissedWorldStepsRemembered", "1")

```
```

setfflag("MaxMissedWorldStepsRemembered", "1000")

```
### Noclip 1
###### Adjust the value so you don't fall through the ground
```

setfflag("AssemblyExtentsExpansionStudHundredth", "-50")

```
### Noclip 2
###### Adjust the value so you don't fall through the ground
```

setfflag("SimBroadPhasePairCountMax", "50")

```
### Noclip 3
###### @burgerboxer & @dis_spencer
```
setfflag("MaximumFreefallMoveTimeInTenths", "1000")
setfflag("DebugSimPrimalStiffness", "0")

```
### Freeze
```

setfflag("FFlagDebugSimDefaultPrimalSolver", "True")
setfflag("DebugSimPrimalLineSearch", "0")

```
### Hip Height
###### Very controllable bounce, only works with negative values, 0 allows you to hover
```

setfflag("MaxAltitudePDStickHipHeightPercent", "-200")

```
### Wallglide
```

setfflag("UnstickForceAttackInTenths", "-4")

```
### Network Ownership
###### better [network ownership](https://create.roblox.com/docs/physics/network-ownership) of parts
###### this might get you banned in some games with anticheats (Limbobbia)
```

setfflag("MinClientSimulationRadius", "2147000000")
setfflag("MinimalSimRadiusBuffer", "2147000000")
setfflag("MaxClientSimulationRadius", "2147000000")

```
### Low Gravity 1
###### 'FFlagDebugSimDefaultPrimalSolver' : True, # Enable the new simulation engine or whatever it is
###### 'DebugSimPrimalLineSearch' : 1, # A poor man's gravity/flight [Default 100] (above 0 is low gravity | below 1 to -1 is will make gameplay weird when it comes to physics | below -1 is a poor mans fly (not really useable) 
###### credit [@Amity](https://www.youtube.com/watch?v=5M411LL17B0)
```

setfflag("DebugSimPrimalLineSearch", "3")

```
### Low Gravity 2 Control on Parts Improvement
```

setfflag("DebugSimPrimalNewtonIts", "1")
setfflag("DebugSimPrimalPreconditioner", "15")
setfflag("DebugSimPrimalPreconditionerMinExp", "10")
setfflag("DebugSimPrimalToleranceInv", "1")
setfflag("DebugSimPrimalWarmstartForce", "-150")
setfflag("DebugSimPrimalWarmstartVelocity", "100")

```
### Backwards SpeedHax
#### Bugginess and Speed depends on the value of `DebugSimPrimalWarmstartForce` values i recommend are `775` and the value i put.
##### Also for `DebugSimPrimalWarmstartVelocity` probably use value `150` but its kinda hard to do it and control
###### I may have not found this first but i found this by myself btw
```

  "DebugSimPrimalNewtonIts", "1")
  "DebugSimPrimalPreconditioner", "69")
  "DebugSimPrimalPreconditionerMinExp", "69")
  "DebugSimPrimalToleranceInv", "1")
  "DebugSimPrimalWarmstartForce", "-885")
  "DebugSimPrimalWarmstartVelocity", "-350")

```

<h1 align="center">Abusive Visuals</h1>

### Humanoid Outline
##### Draws an outline around every part and every humanoid
```

setfflag("DebugDrawBroadPhaseAABBs", "True")

```
### fflag above but more complex
##### Draws an outline around every body part
```

setfflag("DebugDrawBvhNodes", "True")

```
### Xray
```

setfflag("CullFactorPixelThresholdMainViewHighQuality", "10000")
setfflag("CullFactorPixelThresholdMainViewLowQuality", "10000")
setfflag("CullFactorPixelThresholdShadowMapHighQuality", "10000")
setfflag("CullFactorPixelThresholdShadowMapLowQuality", "10000")

```

<h1 align="center">lol</h1>

### Don't Touch The Wall!
```

setfflag("DebugSimPrimalNewtonIts", "-2147483647")
setfflag("DebugSimPrimalToleranceInv", "-2147483647")

```
### Crash Roblox 1
```

setfflag("TimestepArbiterThresholdCFLThou", "0")

```
### Crash Roblox 2
```

setfflag("VideoCaptureServiceEnabled") "False")

```
### Increase Ping 
```

setfflag("DataSenderMaxBandwidthBps", "150")

```

<h1 align="center">Debug</h1>

### Shows the state of a flag
```

setfflag("DebugShowFlagState", "FLAG_HERE")

```
### Show Outlined Chunks that are being interacted
```

setfflag("DebugEnableStreamingSolverVisualization", "True")

```
### Prevents Remote Events from running
```

setfflag("RemoteEventSingleInvocationSizeLimit", "1")

```
### Self Explanatory 1
```

setfflag("DebugPrintDataPingBreakDown", "True")

```
### Self Explanatory 2
```

setfflag("DebugAudioLogging", "True")

```
### Duplicate of Above
```

setfflag("DebugAudioLogging2", "True")

```

<p align="center"><a href="https://raw.githubusercontent.com/MaximumADHD/Roblox-Client-Tracker/roblox/FVariables.txt">FVariables.txt</a></p>
<p align="center"><a href="https://github.com/MaximumADHD/Roblox-FFlag-Tracker">Roblox FFlag Tracker</a></p>

<h4 align="center">© 2024 luafv All Rights Reserved.</h4>
