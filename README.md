# A span-based model for extracting overlapping PICO entities from randomized controlled trial publications

## Overview

This project aims to identify PICO entities from RCT publications. 

Jupyter Notebook is needed `pip install jupyterlab` (see https://jupyter.org/install for details). The root directory contains source files of the pipeline and a folder containing datasets used in the study. The pipeline starts with preprocessing that converts bioc format to jsonl. Next, the boundary detector and span classifier modules are trained. After training, the model can be used for inference, see source files. The code for evaluation is provided at the end. 

Before running the pipeline, please unzip `data.zip` folder under the root and set up the folder to keep input files (including both raw and processed data) and model checkpoints. Please read the beginning of each source file as an example. The full dataset is available at https://github.com/bepnye/EBM-NLP. The default `data` folder setup is as follows:
 
## Citation

If you find our work helpful, please cite:

Zhang G, Zhou Y, Hu Y, Xu H, Weng C, Peng Y. A span-based model for extracting overlapping PICO entities from randomized controlled trial publications. J Am Med Inform Assoc. 2024 Apr 19;31(5):1163-1171. doi: 10.1093/jamia/ocae065. PMID: 38471120; PMCID: PMC11031223.

## Acknowledgement

This project was sponsored by the National Library of Medicine grant R01LM009886, R01LM014344, and the National Center for Advancing Clinical and Translational Science award UL1TR001873.
