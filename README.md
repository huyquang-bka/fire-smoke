# D-Fire: An Image Dataset for Fire and Smoke Detection

**Authors:** Researchers from Gaia, solutions on demand (GAIA)

## About

D-Fire is an image dataset of fire and smoke occurrences designed for machine learning and object detection algorithms, containing more than 21,000 images.

- **Number of Images by Category:**

  - Only fire: 1,164 images
  - Only smoke: 5,867 images
  - Fire and smoke: 4,658 images
  - None: 9,838 images

- **Number of Bounding Boxes by Class:**

  - Fire: 14,692 bounding boxes
  - Smoke: 11,865 bounding boxes

All images were annotated in the YOLO format with normalized coordinates between 0 and 1. We also provide the `yolo2pixel` function to convert coordinates from YOLO format to pixel coordinates.

## Examples

### Download

- [D-Fire dataset (images and labels)](link_to_dataset)
- Training, validation, and test sets.
- Some surveillance videos.
- Some models trained with the D-Fire dataset.

For more surveillance videos, request your registration on our environmental monitoring website "Apaga o Fogo!" (Put out the Fire!).

## Citation

Please cite the following paper if you use our image database:

**Pedro Vinícius Almeida Borges de Venâncio, Adriano Chaves Lisboa, Adriano Vilela Barbosa:** An automatic fire detection system based on deep convolutional neural networks for low-power, resource-constrained devices. In: Neural Computing and Applications, 2022.

If you use our surveillance videos, please cite the following paper:

**Pedro Vinícius Almeida Borges de Venâncio, Roger Júnio Campos, Tamires Martins Rezende, Adriano Chaves Lisboa, Adriano Vilela Barbosa:** A hybrid method for fire detection based on spatial and temporal patterns. In: Neural Computing and Applications, 2023.
