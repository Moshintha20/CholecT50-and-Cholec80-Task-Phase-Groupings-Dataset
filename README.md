# CholecT50 and Cholec80 Task Phase Groupings (CCTPG) Dataset

The CholecT50 and Cholec80 Task Phase Groupings Dataset (CCTPG) is designed to support research and development in laparoscopic surgical robot assistant systems. This dataset comprises annotated video recordings of laparoscopic cholecystectomy tasks, providing valuable information for advanced computational analysis and robotic assistance development.

## Dataset Overview
The dataset consists of:

Annotated video recordings from the CholecT50 and Cholec80 datasets: High-resolution video sequences capturing various stages of laparoscopic cholecystectomy procedures.
Detailed task phase groupings for each video: Labeled sequences indicating specific surgical phases and tasks.
Ground truth annotations for key surgical phases: Verified annotations for critical phases in the surgical process.   
## Purpose and Applications
The dataset is primarily intended for use in:

Automated Surgical Phase Recognition: Enhancing the accuracy and efficiency of detecting and categorizing different phases of laparoscopic surgery.
Task Analysis: Providing a robust framework for the detailed analysis of surgical tasks, aiding in the improvement of surgical techniques and training.
Robotic Surgical Assistance Development: Supporting the development and validation of robotic systems designed to assist in laparoscopic surgeries, ensuring improved safety and efficacy.
## Technical Details   
### Feature Extraction   
Utilizes a pre-trained Rendezvous model to process image sequences and generate feature vectors.
The model extracts spatio-temporal features crucial for identifying and grouping similar surgical tasks.
### Similarity Comparison
Employs a Comparer module to evaluate similarities between feature vectors using triplet labels.
This module identifies frames within videos to extract short clips containing similar laparoscopic surgical tasks.   
## Dataset Integration and Validation
Integrates data from both the CholecT50 and Cholec80 datasets for comprehensive analysis and validation.
Ensures robust methodology by combining multiple datasets and validating findings with expert surgeons.
## Framework Overview   
Provides an overview of the proposed procedure for searching similar laparoscopic surgical tasks.
Aims to improve the understanding and automation of laparoscopic procedures through advanced computational tools and techniques.
## Results   
Effectively identifies and groups similar frames into video clips for detailed comparison.
New CCTPG dataset includes labeled groups of similar video clips, useful for research on robotic assistants in laparoscopic surgeries.
Tested various similarity score thresholds to identify optimal values, confirming the approach's efficacy.

The dataset is primarily intended for use in developing systems for automated surgical phase recognition, task analysis, and the enhancement of robotic surgical assistance.

## Documentation
Please see [the user guide](./UserGuide.pdf).

## Citation
Please cite this work as:
```bibtex
@Dataset{citeKey,
  author = {Moshintha Isuru Hewavitharana, Binh Tran, Brandon Johns, Elahe Abdi},
  title  = {CholecT50 and Cholec80 Task Phase Groupings Dataset},
  year   = {2024},
  doi    = {10.XXXX/XXXXXXX},
  url    = {https://github.com/Moshintha20/CholecT50_and_Cholec80_Task_Phase_Groupings_Dataset},
}
```
<!-- This is a comment and will not be displayed in the rendered README file 
This work is a companion to [our publication](https://doi.org/10.XXXX/XXXXXXXXX):
```bibtex
@Article{citeKey,
  author  = {Moshintha, Author Name},
  journal = {Journal Name},
  title   = {Title of the Publication Related to the Dataset},
  year    = {2024},
  issn    = {XXXX-XXXX},
  pages   = {XXXXXX},
  volume  = {XX},
  doi     = {10.XXXX/XXXXXXXXX},
}
```
-->

(Optional) If you find this work useful, please message me and share how you used it. I'd love to hear about it. 
You can find me here: [linkedin](https://www.linkedin.com/in/moshintha-hewavitharana/).

This description follows the structure of the example you provided and can be adjusted based on any additional details or preferences you may have. If you have specific sections or content from your research paper you'd like included, let me know!
