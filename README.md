# Anonymous Repository

This anonymous repository provides qualitative examples and performance comparisons between the proposed method and baseline approaches under both multi-view and single-view settings.

> **Note:** Due to PDF rendering issues in the web preview, some text or annotations may not be displayed correctly. Please open the original PDF files through the following links for the complete visualization:
>
> - [multiview.pdf](https://anonymous.4open.science/r/anonymous-31B2/multiview.pdf)
> - [single-view.pdf](https://anonymous.4open.science/r/anonymous-31B2/single-view.pdf)

## Qualitative Examples

### Single-view Setting (RefCOCO)

An example of single-view 3D referring orientation grounding on the RefCOCO dataset. Given a single RGB image, its depth map, and camera parameters, the method identifies the referred object (e.g., the woman in the blue shirt) and estimates its 3D bounding box and orientation.

### Multi-view Setting (ScanNet)

An example of multi-view 3D referring orientation grounding on the ScanNet dataset. Multiple RGB-D frames with corresponding camera poses are integrated to reconstruct the scene, localize the referred object (e.g., a cabinet), and predict its 3D orientation.