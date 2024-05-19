# Instructions for Running the Notebook for Testing the Model

## **Instruction 1 no longer works**
- Recently many users have been encountering an issue where google colab no longer loads on github.
- proof that this is a recent issue: [stackoverflow post](https://stackoverflow.com/questions/78501731/error-nbformat-when-uploading-to-github-from-google-colab)
- **to fix this**: click on the following link: [jupyter renderer](https://nbviewer.org/) and paste in the link of the ipynb file found on this github
- the following is the link if needed: https://github.com/joestrada1022/ASL_CNN_Model/blob/main/ASL_Model.ipynb
- once 'open in google colab' is pressed, can go straight to instruction 2

1. **Initialize the Notebook**
- After clicking on the file in github, press 'open in colab'
- run the initialization cell to import all necessary libraries

2. **Load LabelBinarizer**
- navigate to Dataset Handling -> Scaling/Reshaping the Dataset
- run everything under that heading

3. **Load Model**
- there are two sections for the model. One for the ANN and one for the CNN.
- in the specific section, navigate to after the cell where the model is training (the one with the epochs)
- there should be a cell with google drive download links and a model load function.
- run that cell

4. **Run live video**
 - in the Live Video Input section, run everything under 'helper functions'
 - if everything was done correctly, running the 'Camera feed' cell should bring up the live video
 - From there, it should work automatically

**Note**
- to stop the video, follow the instructions on the video popup

