# Tech Xperience Philips
Implementation of an object-recognition AI algorithm from a small dataset for the Philips challenge in the Tech Xperience competition

## Instructions (Docker)
1. Store all the images of the test data set in a folder of your choice and copy the absolute path of that folder

![Test folder example](https://github.com/Seve1995/Tech_Xperience_Philips/blob/master/Test_Folder.png "Test folder")

2. Open the terminal and execute the following command to pull the project's image from my registry:

`docker pull giuseppeseverino/tech_xperience:v1`

3. Run the following command, setting the absolute path of the folder containing the test data:

`docker run -it -v <absolute path to test images>:/philips/Images giuseppeseverino/tech_xperience:v1 python predict.py`

The output will appear in the console, as shown in the screenshots below:

(Linux)
![Linux screenshot](https://github.com/Seve1995/Tech_Xperience_Philips/blob/master/Ubuntu_Tutorial.png "Ubuntu execution")

(Windows)
![Windows screenshot](https://github.com/Seve1995/Tech_Xperience_Philips/blob/master/Powershell_Tutorial.png "Windows execution")
