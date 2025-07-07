# ClusterProfile: Radial Intensity Profiles Analysis Tool For Protein Clusters

## Description

ClusterProfile is a custom ImageJ script designed for automated analysis of radial intensity profiles around myosin clusters in microscopy images. This tool streamlines the identification and quantitative analysis of protein clusters, enabling users to efficiently measure and compare fluorescence intensity distributions. The script was utilized in Petzold et al. 2025 (DOI: (https://github.com/login?return_to=https%3A%2F%2Fgithub.com%2Fngimber%2FClusterProfile](https://doi.org/10.1083/jcb.202305059) to analyze the spatial relationship between myosin and microtubules.

## Features

* **Automated Background Subtraction:** Uses ImageJ’s ‘Moments’ algorithm ([Moments](https://doi.org/10.1016/0734-189x%2885%2990133-1)) for robust background removal.
* **Cluster Identification:** Employs the ‘Find Maxima’ function of ImageJ ([Find Maxima](https://doi.org/10.1038/nmeth.2089)) to accurately locate myosin cluster centers.
* **Radial Intensity Profiling:** Measures intensity profiles in multiple channels around the detected cluster centers.

## Usage

1. Run the ClusterProfile script in ImageJ.
2. Adjust thresholding and maxima detection parameters as needed via the GUI.
3. Automatically export radial intensity profiles for further analysis.

## GUI Preview

![ClusterProfile GUI](https://github.com/ngimber/ClusterProfile/blob/main/ClusterProfile_GUI.PNG)

## GUI Parameters Explained

- **Reference channel:** Select which image channel to use as the reference for cluster detection.
- **Clear background before analysis:** Enable automatic background subtraction before processing.
- **Filter background noise:** Toggle noise filtering to remove small noise artifacts.
- **Size of background noise:** Define the size threshold for noise removal.
- **Tolerated remaining noise level:** Set the acceptable noise level after filtering.
- **Radius:** Specify the radius around cluster centers to measure radial intensity profiles.
- **Toroidal shift (negative control):** Define the shift applied for negative control measurements to validate results.

## Requirements

* ImageJ/Fiji (latest version recommended).
