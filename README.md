# LiDAR Obstacle Detection (Open3D)

![Status](https://img.shields.io/badge/status-learning-blue?style=flat-square)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

> Point cloud processing and obstacle detection using Open3D library with LiDAR data.

Jupyter notebooks and Python scripts for voxel grid filtering, RANSAC plane segmentation, road/obstacle separation, DBScan clustering, and bounding box visualization from LiDAR sensor data.

---

## Topics Covered

- Voxel grid filtering for point cloud reduction
- Region of interest cropping
- RANSAC plane segmentation (road detection)
- Road vs. obstacle separation
- DBScan clustering for obstacle grouping
- Bounding box generation and 3D visualization

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Language | Python |
| 3D Library | Open3D |
| Data | NumPy, matplotlib |
| Package Manager | Poetry |
| Dataset | Udacity LiDAR .pcd files |

---

## Getting Started

```bash
poetry install
jupyter notebook
```

---

## License

MIT
