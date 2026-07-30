# Anonymous Repository

This anonymous repository provides qualitative examples and performance comparisons between the proposed method and baseline approaches under both multi-view and single-view settings.

> **Note:** The PDF preview provided by the web interface may occasionally suffer from rendering issues, where some text or annotations are not displayed correctly. Please use the **Raw** or **Download** option to access the original PDF files for complete visualization:
>
> - [multiview.pdf (Raw)](https://anonymous.4open.science/api/repo/anonymous-31B2/file/multiview.pdf?v=06b27b75)
> - [single-view.pdf (Raw)](https://anonymous.4open.science/api/repo/anonymous-31B2/file/single-view.pdf?v=06b27b75)

## Qualitative Examples

### Single-view Setting (RefCOCO)

An example of single-view 3D referring orientation grounding on the RefCOCO dataset. Given a single RGB image, its depth map, and camera parameters, the method identifies the referred object (e.g., the woman in the blue shirt) and estimates its 3D bounding box and orientation.

### Multi-view Setting (ScanNet)

An example of multi-view 3D referring orientation grounding on the ScanNet dataset. Multiple RGB-D frames with corresponding camera poses are integrated to reconstruct the scene, localize the referred object (e.g., a cabinet), and predict its 3D orientation.