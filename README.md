# Optimize your pc to play roblox using blostrap

## Flags:

Forces Direct3D11 (better performance on newer pcs)

```json
{
  "FFlagDebugGraphicsDisableDirect3D11": false,
  "FFlagDebugGraphicsPreferD3D11": true
}
```

Forces Direct3D10 (better performance on older PCs)

```json
{
  "FFlagDebugGraphicsDisableDirect3D11": false,
  "FFlagDebugGraphicsPreferD3D11": false,
  "FFlagDebugGraphicsPreferD3D11FL10": true,
  "FFlagGraphicsEnableD3D10Compute": true
}
```

Force Voxel Lighting

```json
{
  "DFFlagDebugRenderForceTechnologyVoxel": true
}
```

Disable grass texture

```json
{
  "FIntFRMMinGrassDistance": 0,
  "FIntFRMMaxGrassDistance": 0,
  "FIntRenderGrassDetailStrands": 0,
  "FIntRenderGrassHeightScaler": 0
}
```

Disable Shadows ( only work using voxel lighting )

```json
{
  "DFFlagDebugPauseVoxelizer": true
}
```

High res. lower quality

```json
{
  "DFFlagDisableDPIScale": false
}
```

Disables textures and breaks glass (alternative for one above)

```json
{
  "FStringPartTexturePackTablePre2022": "",
  "FStringPartTexturePackTable2022": "",
  "FStringTerrainMaterialTablePre2022": "",
  "FStringTerrainMaterialTable2022": ""
}
```

Disables player shadows

```json
{
  "FIntRenderShadowIntensity": 0
}
```

Disables some effects (like sunrays)

```json
{
  "FFlagDisablePostFx": true
}
```

Disables antialiasing

```json
{
  "FIntDebugForceMSAASamples": 0
}
```

Makes textures low quality ( use 1 for more quality of texture )

```json
{
  "DFFlagTextureQualityOverrideEnabled": true,
  "DFIntTextureQualityOverride": 0
}
```

Lowers model polygons from far

```json
{
  "DFIntCSGLevelOfDetailSwitchingDistance": 0,
  "DFIntCSGLevelOfDetailSwitchingDistanceL12": 0,
  "DFIntCSGLevelOfDetailSwitchingDistanceL23": 0,
  "DFIntCSGLevelOfDetailSwitchingDistanceL34": 0
}
```

Enables gray sky w/ no clouds

```json
{
  "FFlagDebugSkyGray": true
}
```

Removes most textures of other players

```json
{
  "DFIntTextureCompositorActiveJobs": 0
}
```

Done!
