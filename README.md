Introduction to Convolutional Neural Networks and Computer Vision with TensorFlowComputer vision is the practice of writing algorithms that can discover patterns in visual data, such as a self-driving car's camera recognizing the vehicle in front of it.
This project demonstrates how to build and implement a Convolutional Neural Network (CNN) using TensorFlow to solve a binary image classification problem. 
📂 Dataset InformationThe images used in this project are derived from the Food101 dataset (which originally contains 101 different classes of food).  
For the scope of this project, the dataset has been modified and scaled down using an image data modification script to include only two classes:🍕 Pizza  🍖 Steak  Note: We intentionally start with a smaller dataset so we can experiment quickly and figure out what works (or, better yet, what doesn't work) before scaling up.

🚀 Getting Started1. Structure of the DatasetThe data is structured into standard training and testing directories:  

pizza_steak/
├── train/
│   ├── pizza/  (750 images)
│   └── steak/  (750 images)
└── test/
    ├── pizza/  (250 images)
    └── steak/  (250 images)

Dependency Installation & Setup

🔍 Data Inspection & Visualization
Before feeding data into a neural network, a crucial step in any computer vision project is to "become one with the data" by inspecting directory structures and visualizing image samples.  
Directory VerificationYou can programmatically verify the image distribution using os.walk


🛠️ Tech Stack & Libraries
TensorFlow — Core deep learning framework.
NumPy — For data manipulation and matrix processing.  
Matplotlib — For visual profiling and plotting sample data.  
Pathlib / OS — For file system exploration and pipeline management.  


    
