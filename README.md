# Pranali-shendekar
# Capstone Spring 2023

This capstone project aimed to develop a software tool to manage and process ultrasound imaging data to train deep-learning models to predict the presence of cancerous lesions in breast tissue. The project involved collecting, managing, updating, and summarizing study and annotation data in batches as they become available. The study data included ultrasound images, patient information, biopsy results, BI-RADS scores, and metadata about the images and ultrasound equipment. In addition, the annotation data had additional labels and visual outlines of the lesions, which were provided retrospectively by trained radiologists.

The software tool was designed to extract information from the metadata and text annotations accompanying each image and add it to the master index file. Additionally, the tool had to be able to copy the images to the correct locations in the collection and ensure that the image and patient IDs were distinct from those of previously added data. The tool also allowed for the possibility of overwriting existing data, adding additional columns to the index file, and incorporating corrections. Finally, the tool included additional columns that may be collected later for the annotation data.

Python code was also developed to enable simple filtering of the image data and to write downloaders that allowed retrieving image data from the collection. Finally, to show the efficiency of the database, the dataset was tested on a simple deep learning ResNet50 pre-trained model, and the PyTorch data loaders were used to pass data to the deep learning model. The ultimate goal of this project was to build decision support software that not only predicted the presence of cancerous lesions but also explained how it reached that decision.
Overall, this project contributed to developing a useful tool that can aid in the early detection of breast cancer, leading to better patient outcomes. The software tool developed in this project can be used in further research studies in medical imaging, deep learning, and clinical settings to support radiologists in diagnosing breast cancer.


Keywords: Ultrasound imaging, deep-learning, decision support software, breast cancer diagnosis, biopsy, radiology
