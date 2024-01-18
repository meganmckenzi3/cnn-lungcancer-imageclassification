# Classifying Non-Small Cell Lung Cancer Using CNN
Lung cancer is in the top 3 most diagnosed cancers in the United States of America with an overall 5 year survival rate of 23%. This statistic shows how many people are alive 5 years after a lung cancer diagnosis, specifically for non-small-cell lung cancer which accounts for 90% of lung cancer diagnoses (Dale, 2021). This common cancer has a relatively low survival rate compared to other cancers, and the answer to increasing the survival rate is through early diagnosis and detection. Strategies for early diagnosis rely on medical imaging. This is subjective and susceptible to human error as it depends upon the medical professional viewing the images to identify irregularities on the lungs of patients. What if there was a tool that could be used as a highly-efficient and accurate way to diagnose lung cancer earlier?
AI and deep learning algorithms in healthcare are transformative and increase the accuracy of diagnosis when used with computer vision technology (Kekatos, 2023). Convolutional Neural Networks (CNN) are image based machine learning algorithms that can be used in medical image analysis. The goal will be to design a CNN that can accurately diagnose lung cancer and its type through radiological images. The first CNN model was created using research of common CNN models adapted to a smaller dataset, the second tested CNN model is inspired by the VGG-16 model architecture.

Dale, J. (2021, November 16). New report: Lung cancer survival has increased, but remains significantly lower for people of color. American Lung Association. https://www.lung.org/media/press-releases/solc-2021

Kekatos, M. (2023, July 21). How artificial intelligence is being used to detect, treat cancer -- and the potential risks for patients. ABC News. https://abcnews.go.com/Health/ai-detect-treat-cancer-potential-risks-patients/story?id=101431628#:~:text=Researchers%20are%20using%20machine%2Dlearning,com


**Installation**
This code was written and set up for classification within Google Colab.
1) Access Google Colab and open a new notebook
2) Clone the repository in Google Colab using
!git clone https://github.com/your-username/your-repo.git
3) Or access repository by using Github tab in Colab interface and copying/pasting the Github URL in the search field
4) Upload the Chest CT scan file from repository into Google Colab
5) Run code and explore

**Data Sources**
This image data was sourced from Kaggle as an open source database compilated by author Mohamed Hany from multiple hospital databases. Linked below to download image dataset.
https://www.kaggle.com/datasets/mohamedhanyyy/chest-ctscan-images
This dataset consists of 1,000 labeled images of the 3 subcategories of non-small cell lung cancer and healthy lungs (Adenocarcinoma, large cell carcinoma,  and squamous cell carcinoma).

**Code**

**Results**

**Future Work**
