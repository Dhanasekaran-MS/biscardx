# BizCardX Using Pytesseract library
# BizCardX: Extracting Business Card Data with OCR

## Table of Contents:
1. About The Project
2. Getting Started
   - Prerequisites
   - Installation
3. Usage
4. Steps
5. Run
6. Skills Covered
------------------

## 1. About The Project :

   This project is focused on developing a Streamlit application that allows users to
upload an image of a business card and extract relevant information from it using
'pytesseract Python Module'. The extracted information should include the company name, card holder
name, designation, mobile number, email address, website URL, area, city, state,
and pin code. The extracted information should then be displayed in the application's
graphical user interface (GUI).

## 2. Getting Started :

> Before starting we need to install certain **python** libraries.
-  ### PREREQUISITES :
   + pytesseract
   + re
   + PIL
   + pymysql
   + streamlit
   + pandas - are the Python libraries used in this project
   * Get Youtube API key from [google developer console](https://developers.google.com/youtube/v3/getting-started)
- ### INSTALLATION :
  Run these command separately on your python environment to install.
  
        pip install pytesseract
        pip install pymysql
        pip install streamlit
        pip install pandas
        pip install pillow
        pip install 
   
## 3. USAGE :
   - In this Project, I created a streamlit application that allows users to
upload an image of a business card and extract relevant information from it using
easyOCR. The extracted information should include the company name, card holder
name, designation, mobile number, email address, website URL, area, city, state,
and pin code.
   - The application is simple and intuitive user interface that guides users
through the process of uploading the business card image and extracting its information.
The extracted information will be displayed in a clean and organized manner, and users
should be able to easily add it to the database with the click of a button. And Allow the
user to Read the data, Update the data and Allow the user to delete the data through the
streamlit UI
   

## 4. STEPS :
   1. Import all the libraries that are used in this project.
   2. Created a Connection to MySQL Database
   3. Created streamlit interface sidebar
   4. Creating two tabs one to upload and extract the data and another to modify the data or delete
   5. Created a function to upload a image file and extract text from it using pytesseract and PIL library
   6. Created a Function to order the details corresponding to its nature
   7. Created a button to extract and upload the data to MySQL Database
   8. On Tab2 created dropdowns to modify the data in database or delete a card in database

   > - TO AVOID DUPLICATE REPETATION OF COMPANY WE USED 'PRIMARY KEY' WHILE CREATING TABLES

## 5. RUN :
   > - To Run this project we need to go to terminal and change its path to file_loacted_directory
   > - Then run streamlit code to execute,

           streamlit run file_name.py
   - replace file_name with created python file name
   - To run this project use,

           streamlit run bizcardx.py 
# 6. Skills Covered ✅ ⬇️

    Python (Scripting)
    OCR
    pytesseract
    Regular Expressions
    Data Collection
    SQL
    Streamlit GUI
    
    IDE:  Jupyter, PyCharm Community Version, VS Code

