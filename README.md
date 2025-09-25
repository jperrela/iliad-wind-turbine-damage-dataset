# ILIAD Windmill Damage Dataset

## Overview

The **ILIAD Windmill Damage Dataset** is a curated collection of annotated images of wind turbine blades exhibiting external damage such as cracks, erosion, and delamination. It was created to support research in **computer vision**, **structural health monitoring**, **UAV-based inspections**, and **predictive maintenance** for wind energy systems.

### Key Features
- **Dataset** of wind turbine blades images with visible damage.  
- **Annotations** marking damage types (e.g., crack, delamination, surface erosion).  
- **Diverse conditions**: different lighting, orientations, and environmental factors.  
- **Pre-split** into training, validation, and test sets.  
- Compatible with common ML frameworks (e.g. YOLO, COCO, Pascal VOC).  

The dataset is also listed on the [Ocean Twin Marketplace](https://ocean-twin.eu/marketplace/product/iliad-windmill-damage-dataset).

---

## Repository Structure

```
iliad-windmill-damage-dataset/
├── train/
│   ├── images/
│   └── annotations/
├── valid/
│   ├── images/
│   └── annotations/
├── test/
│   ├── images/
│   └── annotations/
├── data.yaml   # dataset manifest (classes, splits, paths)
├── LICENSE
└── README.md
```

---

## Usage

1. Clone or download this repository.  
2. Load dataset splits (`train/`, `valid/`, `test/`) using your preferred ML framework.  
3. Use `data.yaml` to configure your training pipeline.  
4. Train and evaluate detection or segmentation models (YOLO, Faster R-CNN, Mask R-CNN, etc.).  

---

## License

This dataset is licensed under the **Creative Commons Attribution 4.0 International License (CC BY 4.0)**.  

You are free to:  
- **Share** — copy and redistribute the material in any medium or format.  
- **Adapt** — remix, transform, and build upon the material for any purpose, even commercially.  

Under the following terms:  
- **Attribution** — You must give appropriate credit, provide a link to the license, and indicate if changes were made.  

Full license text: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)  

---

## Acknowledgments

This dataset is part of the ILIAD project and contributes to advancing renewable energy research through better maintenance practices.
