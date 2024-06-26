# HumanAura Additional Content

This repository contains all additional files needed for running HumanAura out of the box without needing to use the utility scripts or original dataset found in the original archive and report. 

Contains:
- 4 exported ONNX models to be supplied to humanaura.py for inference.
- 6 TFRecord Dataset files used for finetuning pre-trained models found in the TensorFlow Object Detection Model Zoo.
- 1 label map file used for finetuning pre-trained models found in the TensorFlow Object Detection Model Zoo.
- 7 Videos sourced from the CAVIAR dataset to be used for inference with humanaura.py, (6 used as subset, 1 bonus video).
- 6 XML ground truth files for converting annotations from, each linked to the 6 subset videos.

This project uses items from the TensorFlow Object Detection Model Zoo and has been adapted for this project.

If there are any issues accessing these files or anything else is needed, please contact me at ml01663@surrey.ac.uk as these large files are stored on Git LFS.     
