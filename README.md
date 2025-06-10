# Applied-Machine-Learning-Cancer-GNN-classification

# Data 
Data was found on the following Kaggle site, where kidney, oral and breast cancer data sets were used.
https://www.kaggle.com/datasets/obulisainaren/multi-cancer/data

Note: The code is computationally intensive and may cause kernel crashes or memory errors on less powerful machines.

# 'Script' 
This script includes the core pipeline for image preprocessing, an initial Convolutional Neural Network (CNN) implementation, autoencoding, and other exploratory components.

# 'Shuffle-script'
The same setup as 'Script', but with shuffle-group-split. This method helps prevent data leakage when multiple images originate from the same subject (e.g., the same patient), ensuring a more reliable model evaluation 

# 'Final-Project'
This project script includes the essential code for processing and analyzing kidney image data. It implements a basic CNN with data augmentation to enhance model performance. Additionally, the script integrates a ResNet-50 architecture and an autoencoder, both applied to the kidney dataset as well as to a separate oral image dataset. The code is structured for clarity and reproducibility, making it suitable for further development or research purposes.

# 'Streamlined_cam' 
This script visualizes model interpretability using two popular techniques: Grad-CAM and Score-CAM.
It highlights the most influential regions of input images based on the trained CNN model, helping to understand and explain model predictions.

# Results 
The two folders contain results from the 'Streamlined_cam' and the file 'Model_summary[...]' is a result from the 'Script' code.

# 'Exam project powerpoint' 
The powerpoint tells the story of the model optimizastion and configurations for the different datasets. It shows the complete workflow, results and code in action. 
