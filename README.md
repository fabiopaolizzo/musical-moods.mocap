# MUSICAL-MOODS: Motion Capture (MoCap) Data

This repository contains the motion capture data component of the MUSICAL-MOODS project, a foundational resource for training and validating AI models on complex, subjective, and unstructured human data.

**For a full overview of the project, please see the [central project hub](https://github.com/fabiopaolizzo/musical-moods.main).**

---

### Data Description

The data in this repository consists of high-dimensional, multi-variate time-series data captured directly from sensors placed on the dancers. This provides a precise, quantitative record of their kinematics during the improvisation, which served as the real-time input for the generative AI music system.

The data is provided in standard BVH format for kinematic analysis.

### Data Acquisition Methodology

The data was captured using an industry-standard **Vicon motion capture system** in a controlled, green screen environment to ensure the highest possible data quality.

*   **Hardware:** 30 Vicon cameras
*   **Software:** VICON Shogun
*   **Marker Set:** A 53-marker configuration (Vicon's "FrontWaist" set)

This professional-grade setup ensures a high degree of precision, accuracy, and reliability in the kinematic data, making it suitable for rigorous scientific analysis and the development of robust machine learning models.

### Potential Applications & Research Areas

This dataset is a rich resource for research in advanced time-series analysis and the modeling of complex systems. It is particularly well-suited for developing and benchmarking models in:

-   **High-Dimensional Time-Series Analysis:** Finding patterns and correlations in complex, multi-variate data streams.
-   **Dynamical Systems Modeling:** Analyzing the behavior of a complex system (the dancer) as it evolves over time.
-   **Representation Learning:** Developing novel embeddings to represent human movement and behavioral states.
-   **Kinematic & Behavioral Analysis:** Building quantitative models of human movement and expression.

---

*This research was supported by the EU's Horizon 2020 programme (MSCA-IF-GF, REA Grant Agreement No. 659434).*
