Mesh warp node is a node in the transform section which allow you to warp an image using control points.
Mesh generation has to be activate manually by clicking on "Generate" button in inspector panel.

| Inputs            | Type        | Description                                          |
| ----------------- | ----------- | ---------------------------------------------------- |
| Surface in        | String      | Image input.                                         |
| Sample size       | Int         | Size (in pixel) of the grid used to subdivide image. |
| Control points... | float[5]... | Position and behavior of control points.             |

| Outputs     | Type    | Description                         |
| ----------- | ------- | ----------------------------------- |
| Surface out | Surface | Image output.                       |
| Mesh data   | Mesh    | Mesh data after the transformation. |

## Preview tools
When previewing this node, an extra toolbar will appear in preview panel.

- **Add / Remove point**: 
  - Click and drag on empty space to add control point. 
  - Click on existed control point to remove it.