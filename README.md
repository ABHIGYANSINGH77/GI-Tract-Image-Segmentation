# GI-Tract-Image-Segmentation

In 2019, an estimated 5 million people were diagnosed with a cancer of the gastro-intestinal tract worldwide. Of these patients, about half are eligible for radiation therapy, usually delivered over 10-15 minutes a day for 1-6 weeks. Radiation oncologists try to deliver high doses of radiation using X-ray beams pointed to tumors while avoiding the stomach and intestines.

With newer technology such as integrated magnetic resonance imaging and linear accelerator systems, also known as MR-Linacs, oncologists are able to visualize the daily position of the tumor and intestines, which can vary day to day. In these scans, radiation oncologists must manually outline the position of the stomach and intestines in order to adjust the direction of the x-ray beams to increase the dose delivery to the tumor and avoid the stomach and intestines. 

To counter this deep learning could help automate the segmentation process, a method to segment the stomach and intestines would make treatments much faster and would allow more patients to get more effective treatment.

Created a model to automatically segment the stomach and intestines on MRI scans.
Used Medical Open Network for AI ([MONAI](https://monai.io/)). PyTorch-based framework for deep learning in healthcare imaging

Data provided by UW-Madison on Kaggle as a part of Kaggle research.

## Segmented Image produced after training the model.

<img width="5000" alt="content_plus_style" src="https://github.com/ABHIGYANSINGH77/GI-Tract-Image-Segmentation/blob/main/Img/segmented_image.PNG?raw=true">
