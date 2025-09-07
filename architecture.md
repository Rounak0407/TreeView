# TreeView Architecture

```mermaid
graph TD
    A[Contributors: Smartphones, Drones, Dashcams, Satellites] --> B[AI Pipeline]
    B --> C[Depth Estimation]
    B --> D[Segmentation]
    B --> E[Object Detection]
    C --> F[Point Cloud + Mesh Fusion]
    D --> F
    E --> F
    F --> G[Scoring Algorithm]
    G --> H[Blockchain Smart Contract]
    H --> I[TREE Token Emission]
