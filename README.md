# USDAssets

This repository provides the official assets used in *Reconciling Reality through Simulation: A Real-to-Sim-to-Real approach for Robust Manipulation*
The manuscript is available on [arXiv](https://arxiv.org/abs/2403.03949). See the [project page](https://real-to-sim-to-real.github.io/RialTo/)

If you use this codebase, please cite

```
@article{torne2024reconciling,
  title={Reconciling Reality through Simulation: A Real-to-Sim-to-Real Approach for Robust Manipulation},
  author={Torne, Marcel and Simeonov, Anthony and Li, Zechu and Chan, April and Chen, Tao and Gupta, Abhishek and Agrawal, Pulkit},
  journal={arXiv preprint arXiv:2403.03949},
  year={2024}
}
```

Go to the [RialTo GUI](https://github.com/real-to-sim-to-real/RialToGUI) to construct more scenes :)

## File structure
- Find the full scenes under `scenes`
- Find the set of objects used to reconstruct the scenes in `objects`
  
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
