# ClinicalVolumes-medical-imaging-software

## Abstract
Background: Modern medical imaging relies on the accurate and rapid image analysis due to the large size of datasets collected on a daily basis both in clinical and pre-clinical imaging, for diagnosis, treatment planning, and research purposes. In order to improve the technology behind such requirements, here we introduce a new image analysis software called ClinicalVolumes. ClinicalVolumes is a semi-automatic image volume analysis tool based on a clustering signal intensity threshold-based method. It has been developed in C++ and can run on both Windows and Mac OS X operating systems. The program is currently available for research use only at https://www.kaggle.com/datasets/prot78/clinicalvolumes. 

Results: ClinicalVolumes has been validated with several MRI applications but it also can process Echocardiography and CT images. MRI datasets of clinical cardiac cases, and pre-clinical mouse models of heart, brain and adipose tissues have been analyzed by the ClinicalVolumes software and results were compared to a full manual segmentation. Bland-Altman analysis, intra- and inter-observer variability are reported for all investigated MRI applications as a numeric validation. The accuracy error was estimated to be below 10% and the segmentation was from 2 to 4 times faster, depending on the application, when compared to a full manual segmentation.
Conclusions: ClinicalVolumes is a fast, robust, user-friendly and accurate tool for image segmentation aimed to improve volume analysis in numerous medical applications ranging from cardiovascular disease to tumor and brain imaging.           

Keywords: segmentation; volumes; MRI; Echocardiography; CT; clinical; pre-clinical; DICOM.
