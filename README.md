# Anonymous Repository

This anonymous repository provides demonstration results and performance comparisons between the proposed method and baseline approaches under both multi-view and single-view settings.

## Demo Results

- **single_image.pdf**
  Demonstrates the inference pipeline under the single-view setting on the RefCOCO+ dataset and provides qualitative comparisons between our method and SpatialReasoner on representative examples.

- **multi_image.pdf**
  Demonstrates the inference pipeline under the multi-view setting on the ScanNet dataset and provides qualitative comparisons between our method and VG-LLM on representative examples.

## Qualitative Examples



### Single-view Setting (RefCOCO)

An example of single-view 3D referring orientation grounding on the RefCOCO dataset. Given a single RGB image, its depth map, and camera parameters, the method identifies the referred object (e.g., the woman in the blue shirt) and estimates its 3D bounding box and orientation.

### Multi-view Setting (ScanNet)

An example of multi-view 3D referring orientation grounding on the ScanNet dataset. Multiple RGB-D frames with corresponding camera poses are integrated to reconstruct the scene, localize the referred object (e.g., a cabinet), and predict its 3D orientation.
