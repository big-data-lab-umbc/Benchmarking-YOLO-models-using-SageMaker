# Benchmarking-YOLO-models-using-SageMaker

## Overview

- **'YOLO-models'**: This directory contains the notebook files for YOLO versions 5, 8, and 9. Version 9 includes both single and multi-GPU notebooks to cater to different hardware configurations.
  
- **'Config-files'**: This directory contains all the configuration files necessary for the models, including data paths and class labels specific to each version of YOLO.

## Setup Instructions

To use the notebooks, follow these steps:

1. **Open Amazon SageMaker in AWS**:
   - Go to the [SageMaker console](https://console.aws.amazon.com/sagemaker/).
   
2. **Upload the files**:
   - Upload the notebooks from the **'YOLO-models'** folder and the configuration files from the **'Config-files'** folder into your SageMaker environment.
   
3. **Prepare the Data**:
   - Ensure that your data is ready and accessible. You should have your dataset uploaded to an S3 bucket, or ensure that your SageMaker environment has access to the data location.

4. **Run the Notebooks**:
   - Open the notebooks in SageMaker.
   - The notebooks are already set up and ready to run. You just need to follow the instructions in the notebook to start training and testing the YOLO models.

## Notes

- **Version 9**: The YOLO version 9 notebooks include options for both single and multi-GPU setups. Make sure to choose the appropriate notebook based on your hardware configuration.
- **Configuration Files**: The configuration files should be updated to match your specific dataset paths and class labels.
