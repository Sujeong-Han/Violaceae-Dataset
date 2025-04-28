# Violaceae-Dataset

Annotated herbarium images and segmentation masks of 36 Violaceae species for automated plant identification.

## Dataset Description

The Violaceae-Dataset consists of 345 herbarium specimen images (~50.9MB) representing 36 species of the Violaceae family native to South Korea.  
Key characteristics of the dataset are as follows:

- **Number of images per species**: 2 to 10 images (most species have 10 images)
- **Specimen sources**: Only domestic herbaria were used. Data from international digital repositories (iDigBio and CVH) are excluded, pending permission requests.
- **Collection site information**:
  - For endangered species (four species: *Viola albida var. chaerophylloides*, *Viola raddeana*, *Viola orientalis*, *Viola diamantiaca*), collection locations have been obscured in gray.
  - GPS coordinates are masked (grayed) for all specimens to protect conservation sites.
- **Selection criteria**:
  - **Phenological stages**: Preferably five flowering stage images and five fruiting stage images per species
  - **Diverse herbarium sources**: Images sourced from multiple herbaria when available
  - **Digitization methods**: Balanced inclusion of scanned and photographic images

## Folder Structure

- `images/` : Resized specimen images organized by species folders (e.g., V01, V02, ..., V36).

## How to Use

1. Download the `images/` folder.
2. Each subfolder (e.g., V01, V02, ...) corresponds to a specific plant species.
3. All image files are provided in JPEG format and resized to a uniform height of 1000 pixels while maintaining the original aspect ratio.

*(Segmentation masks will be uploaded soon.)*

## Citation

Citation information will be updated upon the publication of the related article.

