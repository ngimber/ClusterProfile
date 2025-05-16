# ClusterProfile: Radial Intensity Profiles Analysis Tool

## Description

ClusterProfile is a custom ImageJ script designed for automated analysis of radial intensity profiles around myosin clusters in microscopy images. This tool streamlines the identification and quantitative analysis of protein clusters, enabling users to efficiently measure and compare fluorescence intensity distributions. The script was used in Petzold et al. 2025 (DOI:) to analyze the spatial relationship of myosin and microtubules. 

## Features

* **Automated Background Subtraction:** Uses ImageJ’s ‘Moments’ algorithm ([DOI](https://doi.org/10.1016/0734-189x%2885%2990133-1)) for robust background removal.
* **Cluster Identification:** Employs the ‘Find Maxima’ function of ImageJ ([DOI](https://doi.org/10.1038/nmeth.2089)) to accurately locate myosin cluster centers.
* **Radial Intensity Profiling:** Measures intensity profiles in multiple  channels around the detected cluster centers.

## Usage

1. Load your microscopy images into ImageJ.
2. Apply the ClusterProfile script.
3. Adjust thresholding and maxima detection parameters as needed.
4. Visualize and export radial intensity profiles for further analysis.

## Requirements

* ImageJ/Fiji (latest version recommended).

## Installation

Clone this repository using:

```bash
git clone https://github.com/ngimber/ClusterProfile.git
```

## License

This project is licensed under the MIT License.
