# USDAssets
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
