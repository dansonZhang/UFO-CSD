# UFO-CSD: Ultra-wide Field-of-view distorted camera light-Object Curve Segment Drawing
**Status:** Paper under review (*Pattern Recognition*). Code & dataset will be released upon acceptance.
![UFO-CSD Overview](./Figures/UFO-CSD_overview_EN.png)

## What It Solves

UFO-CSD rapidly extracts **complete, reliable curves from heavily distorted fisheye and panoramic images**—without undistortion and without loss of edge detail.

## Why It’s Different

* **Undistortion‑free, spherical processing** – operates directly on the equivalent spherical surface of raw distorted frames, preserving every pixel and all peripheral detail.

* **Omnidirectional growth in milliseconds** – gradient‑ and distance‑constrained exploration rapidly sketches curve skeletons across the full FoV.

* **Integrity verification & global stitching** – geometric checks reunite consistent segments and suppress outliers, delivering complete, reliable curves.

* **Real‑time on edge devices** – up to 10 × faster with higher detection rate and lower localization error than state‑of‑the‑art, even without a dedicated GPU.

## Visualizations
![Light-object curve detection in fisheye image](./Figures/fish-lo-result.png)
![Light-object curve detection in panoramic image](./Figures/pano-lo-result.png)
![Curve detection in ZJSU dataset](./Figures/ZJSU-results.png)
## Coming Soon

Installation guide will appear here after publication.

```bibtex
@article{zhang2025ufocsd,
  title   = {UFO-CSD: Ultra-wide Field-of-view distorted camera light-Object Curve Segment Drawing},
  author  = {Zhixiong Zhang and et al.},
  journal = {Pattern Recognition},
  year    = {2025},
  note    = {Under review}
}
```

**License:** Planned Apache 2.0
