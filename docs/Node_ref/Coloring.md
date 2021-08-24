# Coloring

## Colorize

Remap greyscale pixel with user defined gradient.

![](../img/nodes/node_colorize.png)

| Inputs     | Type     | Description      |
| ---------- | -------- | ---------------- |
| Surface in | String   | Image input.     |
| Gradient   | Gradient | Color to map to. |

| Outputs     | Type    | Description   |
| ----------- | ------- | ------------- |
| Surface out | Surface | Image output. |

## Posterize

Average color in an image into palette.

![](../img/nodes/node_posterize.png)

| Inputs     | Type    | Description    |
| ---------- | ------- | -------------- |
| Surface in | String  | Image input.   |
| Palette    | Color[] | Output colors. |

| Outputs     | Type    | Description   |
| ----------- | ------- | ------------- |
| Surface out | Surface | Image output. |

## Dither

Apply dither effect.

![](../img/nodes/node_dither.png)

| Inputs     | Type    | Description        |
| ---------- | ------- | ------------------ |
| Surface in | String  | Image input.       |
| Palette    | Color[] | Output colors.     |
| Pattern    | Int     | Dither pattern.    |
| Dither map | Surface | Custom dither map. |

| Outputs     | Type    | Description   |
| ----------- | ------- | ------------- |
| Surface out | Surface | Image output. |
