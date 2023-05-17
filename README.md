# Auto_Recognition
Code Academy Data Science Final Project

Clone project to your local directory:
1. Open Command Prompt (search CMD)
2. Open prefered directory use command 'cd'. For example: cd C:\Users\jolged\PycharmProjects
3. run command: 'git clone git@github.com:Jolita-byte/Auto_Recognition.git'

Prepare virtual environment:
1. Open Command Prompt (search CMD)
2. Open preferred directory use command 'cd'. For example: cd C:\Users\jolged\PycharmProjects\Auto_Recognition
3. Create virtual environment. Run command: 'python -m venv virtual_env'
4. Activate virtual environment. Run command: 'virtual_env\Scripts\activate'
5. Install libraries. Run command: pip install -r C:\Users\jolged\PycharmProjects\Auto_Recognition\requirements.txt

Catalogs:
- **data** - data catalogs:
  - **collection_latest** - catalog created after running function, which collects latest sample photo from each camera 
  - **v1.1.1** - data collected from camera with id of 364. It has separated collections of data for training and for testing. 
    - **ambiguous** has ambiguous photos, which was not included neither to training nor testings. 
    - **test** - test data set
      - **0** catalog has photos with no car in it
      - **1** catalog has photos with cars in it
    - **train** - train data set
      - **0** catalog has photos with no car in it
      - **1** catalog has photos with cars in it
  -**info.txt** - file with some info about data set
- **models** - catalog with models and trheir output
  - **model_v1.1.0_tryx** - Xth model catalog
    - **model_v1.1.0_tryx.hdf5** - trained model file
    - **outputs** - model output files and pictures
- **src** - script file catalog
  - **auto_aptikimas_augmentations.ipynb** - script for data augmentations
  - **auto_aptikimas_data_collecting.ipynb** - script for data collecting
  - **auto_aptikimas_model_and_training.ipynb** - script for custom model and its training with run logging to Wandb
  - **auto_aptikimas_Presentation.ipynb** - main project script with visualisations and work process.

