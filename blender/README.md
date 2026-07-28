## Blender Dataset Generator

This folder contains the final Blender script used to generate the synthetic Structure-from-Motion dataset.

### Output

The script generates:

* 54 rendered images
* camera intrinsics
* camera poses
* ground-truth point cloud
* ground-truth mesh
* visibility matrix
* 2D↔3D correspondences

### Camera Sampling

* 3 orbits: -20°, 0°, +20°
* 18 views per orbit
* Total: 54 images

### Usage

1. Open Blender.
2. Load the skull model.
3. Open the Scripting workspace.
4. Run `dataset_generator.py`.

The dataset will be generated in the `SfM_Dataset` folder.
