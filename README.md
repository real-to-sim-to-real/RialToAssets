# USDAssets
This repository contains all of the assets used in RialTo.

`objects`: contains the multiple distractor objects

`scenes`: contains the scenes for each task

## Convert USDZ to GLB files
- Install aspose-3d
```
pip install aspose-3d
```

- Run the code below:

```
import aspose.threed as a3d

scene = a3d.Scene.from_file("input.usd")
scene.save("output.glb")
```
