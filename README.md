In my final semester at WVU, I completed a few projects in an independent study course. These are described below. Note that all of them were completed on Kaggle first, then copied over to this repo at a later date. Use this link to access my Kaggle: https://www.kaggle.com/gabecardella: 

### Project 1: Weather API Requests
In Kaggle, I created a tool that, once a day, obtains the current weather information (current temperature and feels-like temperature) of Morgantown, WV. Each new day of data automatically gets pulled without having to manually run the associated Kaggle notebook, as well as gets appended to a pre-existing data table with all other days' information. A graph is also automatically updated and displayed with the new day's information.

Because of the reliance of Kaggle for this project, I just provide a link to the Kaggle notebook below:
https://www.kaggle.com/code/gabecardella/ds495-weatherapirequests

### Project 2: Topic Modeling:
Using Amazon customer reviews of appliances, created an LDA Topic Modeling Model that identifies the underlying topics that are found in the large corpus of reviews. These reviews were preprocessed and cleaned as well. I then visualized each topic using documents (cleaned reviews) high concentration of a specific topic to discover insights regarding what each topic represents.

Note that due to a very large file size, the "Appliances.json" file that is referenced when reading in the data is not present (git lfs still being worked out). For the time being, feel free to download the appliances dataset from the link at the top of the .ipynb file.

### Project 3: Lego Image Classification
Created several Convolutional Neural Network (CNN) models to predict the type of Lego Brick that was present in images of Lego pieces. There were a total of 16 (balanced) classes of Lego Bricks, with the best model having an accuracy of 89%. I utilized data generators (to read the image data in batches from a directory and introduce modified images), GPUs, and transfer learning using the VGG16 pre-trained CNN from ImageNet.

Because of the reliance of Kaggle in this project (and the use of Kaggle's pre-built directories), I link the associated Kaggle notebook below:
https://www.kaggle.com/code/gabecardella/ds-495-image-processing

### Project 4: Image Processing on WVU HPCs
Through the use of SLURM job submissions, allocation of CPU and GPU nodes, and batch processing, I transferred all code from Project 3 onto WVU's "Thorny Flat" HPC.
