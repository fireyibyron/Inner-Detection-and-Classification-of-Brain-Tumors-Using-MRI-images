# Inner-Detection-and-Classification-of-Brain-Tumors-Using-MRI-images
This is a thesis based project for Computer Engineering bachelor's degree.

This project was coded on two platforms using Python as the programming language.

///$$$$$$$No password is required to access the project$$$$$$$///

# Steps on how to run the program

  1. Download the "dataset" and "Inner-Detection-and-Classification-of-Brain-Tumors-Using-MRI-images" zipfiles (If the raws are not 
    showing on "Inner-Detection-and-Classification-of-Brain-Tumors-Using-MRI-images" file then click the "View raw" link to download the 
    file)
  2. Unzip both files "dataset and Inner-Detection-and-Classification-of-Brain-Tumors-Using-MRI-images"
  3. Add the "dataset" folder to "the Inner-Detection-and-Classification-of-Brain-Tumors-Using-MRI-images" folder under Project model folder
  4. After successfully completing set 1 and 2 open the "Inner-Detection-and-Classification-of-Brain-Tumors-Using-MRI-images" folder  
     with any coding software platform that handles python language. Preferably Visual Studio Code is recommended if possible and the 
     latest version of python.
  5. Install the required Python libraries listed on the "requirements.txt" file of the project and some additionals as needed.
  6. copy the file path link of the MRI image of your choice from the test dataset and paste like the example below:

               # Loading the image and mask in grayscale
               mri_image = cv2.imread('dataset/Testing/glioma_tumor/image(9).jpg', cv2.IMREAD_GRAYSCALE)
               mask = cv2.imread('dataset/Testing/glioma_tumor/image(9).jpg', cv2.IMREAD_GRAYSCALE)
   
  7. Run the app.py file in python language. 

NB: Steps 6 and 7 also apply to the Kaggle version, however on kaggle there is no need of the latest python installation. kaggle provides the latest version since it is an online platform.
If needed run the main.py file but first first delete the existing "braintumors10epochs.h5" file then uncomment the saving model code line below on main.py code:

              # # Saving the trained model
              # model.save('braintumors10epochs.h5')


///$$$$$$all files must be in the same directory$$$$$$$///
///$$$$$$$Thank you!!!!$$$$$$$$///
