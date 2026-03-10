# jellyfish-pqc6u-ftpov-gjvb > 2026-03-02 1:52am
https://universe.roboflow.com/anthonys-workspace-y3qpf/jellyfish-pqc6u-ftpov-gjvb-jm40z

Provided by a Roboflow user
License: MIT

# Overview
- [Introduction](#introduction)
- [Object Classes](#object-classes)
  - [Jellyfish](#jellyfish)

# Introduction
This dataset aims to solve the task of detecting jellyfish in marine environments. Jellyfish are marine animals recognizable by their gelatinous, umbrella-shaped bodies and tentacles. Accurate identification of jellyfish is crucial for marine monitoring and research.

- **Jellyfish**: A marine animal with dome shaped bodies and tentacles slightly below the water surface.

# Object Classes

## Jellyfish

### Description
Jellyfish are characterized by their translucent, dome-shaped bodies and flowing tentacles. In the images, they appear as light, round figures often slightly below the water surface, creating a faint, circular silhouette.

### Instructions
  - Enclose the entire visible area of the jellyfish, including the dome and any discernible tentacles.
  - The bounding box should cover the translucent part of the jellyfish, accounting for any visible distortion caused by water movement.
  - Do not include reflections or shadows in the bounding box.
  - If jellyfish are partially obscured by water or debris, annotate only the visible parts.
  - If multiple jellyfish are overlapping, create separate bounding boxes for each distinguishable individual.