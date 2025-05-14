---
title: Misc
icon: ellipsis
order: -9
---

### Replace all Decals with a Test Image 
@.rbx.bloxy
```json
{
    "FFlagDebugTestImageDrawItem": "True"
}
```
### Shows the state of a flag
```json
{
    "FStringDebugShowFlagState": "FLAG_HERE"
}
```
#### e.g
```json
{
    "FStringDebugShowFlagState": "DFIntTaskSchedulerTargetFps, ChannelName"
}
```
### Show Outlined Chunks
```json
{
    "FFlagDebugLightGridShowChunks": "True"
}
```
### Show Outlined Chunks that are being interacted
```json
{
    "DFFlagDebugEnableStreamingSolverVisualization": "True"
}
```
### Prevents Remote Events from running
@spectroscopic
```json
{
    "DFIntRemoteEventSingleInvocationSizeLimit": "1"
}
```
### Show All Error Strings
```json
{
    "FFlagDebugEnableErrorStringTesting": "True"
}
```
### logs stuff in dev console
```json
{
    "FStringDebugLuaLogLevel": "verbose",
    "FStringDebugLuaLogPattern": "ExpChat/mountClientApp"
}
```
### Octree Validation
```json
{
    "FFlagDebugEnableOctreeValidation": "True"
}
```
### _crash
> [!IMPORTANT]
> **Studio Only**
```json
{
    "FFlagDebugCrashEnabled": "False"
}
```
### Self Explanatory 1
```json
{
    "DFFlagDebugPrintDataPingBreakDown": "True"
}
```
### Self Explanatory 2
```json
{
    "DFFlagDebugAudioLogging": "True"
}
```
### Duplicate of Above
```json
{
    "DFFlagDebugAudioLogging2": "True"
}
```
### Self Explanatory 3
```json
{
    "FFlagTrackerLodControllerDebugUI": "True"
}
```
### Self Explanatory 4
> [!NOTE]
> **Disable Drag Detectors**
```json
{
    "FFlagDragDetectors1": "False"
}
```
### Self Explanatory 5
> [!NOTE]
> **Disable CTM Climbing**
```json
{
    "FFlagUserClickToMoveSupportAgentCanClimb2": "False"
}
```
### Self Explanatory 6
> [!NOTE]
> **Disable Feedback Button in ESC**
```json
{
    "FFlagDisableFeedbackSoothsayerCheck": "False"
}
```
### Self Explanatory 7
@thefrenchguy4
```json
{
    "FFlagRenamePassesAndGearToSubscriptionsAndPasses": "False"
}
```
### Self Explanatory 8
```json
{
    "DFFlagDebugSimulateHangAtStartup": "True"
}
```
### Self Explanatory 9
```json
{
    "DFFlagDebugSimulateHangAtShutdown": "True"
}
```
### Self Explanatory 10
> [!NOTE]
> **LDL Program Stats**
```json
{
    "DFFlagDebugSimLDLProgramPrintBuildStats": "True",
    "DFFlagDebugSimLDLProgramPrintExecStats": "True"
}
```
### Self Explanatory 11
```json
{
    "FFlagDebugCountSimBodyAllocations": "True"
}
```
### Self Explanatory 12
```json
{
    "FIntNewDevConsoleMaxLogCount": "2147483647"
}
```
### Self Explanatory 13
```json
{
    "FFlagDebugAlwaysDisplayRenderStats": "True"
}
```
### Self Explanatory 13
###### set to 0 for the super fps boost trust it works
> [!NOTE]
> **Default value is 650, higher value more usage lower value less**
```json
{
    "FIntRenderMaxShadowAtlasUsageBeforeDownscale": "650"
}
```
### Self Explanatory 14
> [!NOTE]
> Allows you to edit the DataModel Patch
```json
{
    "FFlagDataModelPatcherForceLocal": "True"
}
```
