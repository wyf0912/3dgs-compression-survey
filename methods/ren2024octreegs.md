### Octree-GS: Towards Consistent Real-time Rendering with LOD-Structured 3D Gaussians
Octree-GS introduces an octree structure to 3D Gaussian splatting. Starting with a sparse point cloud, an octree is constructed for the bounded 3D space, where each level corresponds to a set of anchor Gaussians assigned to different levels of detail (LOD). This method selects the necessary LOD based on the observation view, gradually accumulating Gaussians from higher LODs for final rendering. The model is trained using standard image reconstruction and volume regularization losses.