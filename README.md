# Eye Tracking Experiment using WebGazer

This repository contains the implementation, data analysis, and report for an eye-tracking experiment conducted as part of the course ELEC-E7852 Computational Design Interaction during Fall 2024 at Aalto University. The experiment utilized WebGazer to track eye movement across different UI iterations and analyzed visual attention patterns.

See the full report:

---

## Overview

The primary objective of this assignment was to explore the use of eye-tracking software in user interface analysis. This was achieved by:

1. Calibrating an eye-tracking tool using WebGazer.
2. Gathering and processing eye-tracking data.
3. Visualizing and analyzing user attention flow across UI iterations.

The findings, while insightful, revealed limitations in the precision of the software and bias introduced during the experimental setup.

---

## Technologies & Tools

- **WebGazer**: For eye-tracking functionality ([GitHub link](https://github.com/brownhci/WebGazer))
- **JavaScript**: To implement the UI calibration and eye-tracking logic.
- **Python (Jupyter Notebook)**: For data cleaning, normalization, and visualization.
- **ChatGPT**: Assisted in debugging, data normalization, and visualization refinement.

---
## Experimental Setup
- Setup: WebGazer was installed using Brew and Node.js. Dependencies were resolved using an older version of Node.js. To run the code, run the main.js file after the WebGazer has been installed.
- Calibration: Participants were asked to calibrate the software by clicking dots while focusing on them.
- Data Collection: Eye movements were recorded during interactions with three UI iterations of a Fazer Café website.
- Analysis: Data was normalized, visualized, and analyzed using Python.

## Results
- The participant's gaze primarily focused on the middle and bottom areas of the UI, with consistent attention to the "Log In" button in the upper-right corner.
- Variations in layout did not produce significant differences in gaze patterns.
- Calibration biases and software limitations were observed.

## Discussion & Conclusions
- Insights: The experiment suggested that middle-screen elements capture user attention, but conclusions on UI iteration effectiveness remain inconclusive.
- Limitations: A single participant, calibration biases, and software inaccuracies highlight the need for more robust experimental setups.
- Future Work: Including more participants and using precise tracking tools could improve reliability.

## Acknowledgments
This assignment was completed as part of the course ELEC-E7852 taught by Antti Oulasvirta during Fall 2024. Special thanks to WebGazer developers for the open-source eye-tracking tool.

## References:
https://webgazer.cs.brown.edu/
