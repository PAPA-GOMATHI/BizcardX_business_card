# BizcardX_business_card
BizCardX: Extracting Business Card Data with OCR

INTRODUCTION -
--------------------------------------------
1. BizCardX is a user-friendly tool for extracting information from business cards. The tool uses OCR technology to recognize text on business cards and extracts the data into a SQLite database after classification using regular expressions
2. Users can access the extracted information using a GUI built using streamlit. The BizCardX application is a simple and intuitive user interface that guides users through the process of uploading the business card image and extracting its information
3. The extracted information would be displayed in a clean and organized manner, and users would be able to easily add it to the database with the click of a button
4. Further the data stored in database can be easily Read, updated and deleted by user as per the requirement

IMPORTING PACKAGES FOR THIS PROJECT - 
----------------------------------------------
1. Pandas
2. Streamlit
3. SQLite
4. EasyOCR
5. Pillow

PROJECT APPROACH - 
-------------------------------------------------
1. Install all the required packages using -"pip install"
2. Set the streamlit page configurations like background, Page icon, title , markdown, option with help of using the html tags
3. Perform the Regular expression work for extracting the text from the given image
4. To Upload & Extract the text from the given images only we are using easyocr module
5. To Update, Delete, Read operations on the given text images , to storing that data by using sqlite3 and after that we can commit any changes or deletion by selecting the name on the dropdown list

Thank you!
