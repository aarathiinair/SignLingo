

# SignLingo

SignLingo is an innovative software project designed to bridge communication gaps between users of Indian Sign Language (ISL) and American Sign Language (ASL). Our application leverages machine learning algorithms to provide real-time translation between these two widely used sign languages. By facilitating seamless communication, SignLingo aims to foster greater understanding and connection between deaf communities across different cultural contexts. Whether you're a sign language user, an interpreter, or someone interested in cross-cultural communication, SignLingo offers a powerful tool to break down language barriers and promote global deaf communication.

Key ML models behind SignLingo:
* SVM: Classifies hand signs with high accuracy
* GridSearchCV: Fine-tunes our model for optimal performance
* StandardScaler: Normalizes data for consistent sign recognition.

## How to Run SignLingo
Follow these steps to set up and run SignLingo on your local machine:  

#### Prerequisites:
* Python 3.x 
* pip (Python package installer)
* MySQL server
* ASL and ISL image files for each letter

#### Populate the Database:
1. Place your ASL and ISL image files in a known directory.
2. The script assumes they are in C:/Program Files/MySQL/MySQL Server 8.0/Uploads/.
3. Update the image file paths in the database population script if your images are stored elsewhere.
4. Run the database population script:
   python add_imgs_to_db.py.py
  This script will insert the images for each letter into the translation_table.

#### Configuration
Open app.py and add_imgs_to_db to update the MySQL connection details if necessary:
>>host="localhost",
>>user="root",
>>password="ArteryNoir#5",
>>database="aarathi"

#### Running the Application
1. Start the main application:
  python app.py
2. Open your web browser and navigate to http://localhost:5001 or http://127.0.0.1:5001 to access the SignLingo interface.






<br>
<br>



<div style="clear: both; margin-top: 20px; margin-bottom: 20px;">
  <div align="center">
    <figure>
      <img src="website pictures and gif/front page - 1.png" alt="SignLingo Front Page" width="600">
      <figcaption>Figure 1: Front page of the SignLingo application</figcaption>
    </figure>
  </div>
</div>












