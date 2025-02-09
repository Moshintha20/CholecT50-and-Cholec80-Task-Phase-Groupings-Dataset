# CholecT50 and Cholec80 Task Phase Groupings (CCTPG) Dataset

In order to train laparoscopic robotic assistants to accurately and quickly identify the stages of laparoscopic surgical procedures, it is crucial to have a well-structured dataset. This dataset not only facilitates the training of new endeavors but also aids in effectively categorizing video clips for easy understanding and classification. The CholecT50 and Cholec80 Task Phase Groupings Dataset (CCTPG) is meticulously organized based on triplet labels: Instrument, Verb, Target and designed to support research and development in laparoscopic surgical robot assistant systems. This dataset comprises annotated video recordings of laparoscopic cholecystectomy tasks, providing valuable information for advanced computational analysis and robotic assistance development.

## Dataset Overview
The dataset consists of:

 - Annotated small video clips extracted from the CholecT50 and Cholec80 datasets.
 - Detailed triplet labeled based groupings for each video: Labeled sequences indicating the video number and frame number.

The dataset is primarily intended for use in developing systems for automated surgical phase recognition, task analysis, and the enhancement of robotic surgical assistance.

## Dataset Description
This dataset is structured around defined similarity thresholds, organized into triplets. It includes video clips named in accordance with the conventions used in the CholecT50 and Cholec80 datasets, which cover similar surgical tasks. Folders with similarity scores above 0.975 contain 11 subfolders labeled by triplets, while those above 0.985 contain 4 subfolders. Each subfolder contains video clips following the naming convention:

VID\(video number 1\)_\(frame number\)\_and_VID\(video number 2\)\_\(frame number\)_a.mp4


In this naming convention:

 - video number 1 represents the first video of the similarity pair.
 - frame number represents the frame number of the first video.
 - video number 2 represents the second video of the similarity pair.
 - frame number represents the frame number of the second video.
   
The suffix a or b at the end of the filename indicates which frame the video clip is for:

 - a indicates the video clip corresponds to the frame from video number 1.
 - b indicates the video clip corresponds to the frame from video number 2.
   
This structured approach ensures clear identification and organization of video clips based on their similarity pairs and frames. To help users understand which group number represents which triplet label, a 'triplet_labels.txt' file is provided in the dataset folder. 



<!--
## Citation
Please cite this work as:
```bibtex
@Dataset{citeKey,
  author = {Moshintha Isuru Hewavitharana and Binh Tran and Brandon Johns and Elahe Abdi},
  title  = {CholecT50 and Cholec80 Task Phase Groupings Dataset},
  year   = {2024},
  doi    = {10.XXXX/XXXXXXX},
  url    = {https://github.com/Moshintha20/CholecT50-and-Cholec80-Task-Phase-Groupings-Dataset},
}
```
 This is a comment and will not be displayed in the rendered README file 
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
##
(Optional) If you find this work useful, please message me and share how you used it. I'd love to hear about it. 
You can find me here: [linkedin](https://www.linkedin.com/in/moshintha-hewavitharana/).

This description follows the structure of the example you provided and can be adjusted based on any additional details or preferences you may have. If you have specific sections or content from your research paper you'd like included, let me know!

## License
This work is derivative of the [CholecT50 and Cholec80 Datasets](http://camma.u-strasbg.fr/datasets/)

The dataset and documentation are distributed under the [Creative Commons CC BY-NC-SA 4.0 license](https://creativecommons.org/licenses/by-nc-sa/4.0/)
