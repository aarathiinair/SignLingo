

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
<p align="center">
  <img src="website pictures and gif/front page - 1.png" alt="SignLingo Front Page" width="600">
</p>
<p align="center">
  <em>Figure 1: Front page of the SignLingo application</em>
</p>
<br>
<br>
<p align="center">
  <img src="website pictures and gif/ISL -letter p.png" alt="ISL Letter P" width="600">
</p>
<p align="center">
  <em>Figure 2: Indian Sign Language (ISL) representation of the letter P</em>
</p>
<br>
<br>
<p align="center">
  <img src="website pictures and gif/isl - B.png" alt="ISL Letter B" width="600">
</p>
<p align="center">
  <em>Figure 3: Indian Sign Language (ISL) representation of the letter B</em>
</p>
<br>
<br>
<p align="center">
  <img src="website pictures and gif/isl - letter A.png" alt="ISL Letter A" width="600">
</p>
<p align="center">
  <em>Figure 4: Indian Sign Language (ISL) representation of the letter A</em>
</p>
<br>
<br>
<p align="center">
  <img src="website pictures and gif/isl - letter V.png" alt="ISL Letter V" width="600">
</p>
<p align="center">
  <em>Figure 5: Indian Sign Language (ISL) representation of the letter V</em>
</p>
<br>
<br>
<p align="center">
  <img src="website pictures and gif/asl - letter Lpng.png" alt="ASL Letter L" width="600">
</p>
<p align="center">
  <em>Figure 6: American Sign Language (ASL) representation of the letter L</em>
</p>
<br>
<br>
<p align="center">
  <img src="website pictures and gif/asl - letter d.png" alt="ASL Letter D" width="600">
</p>
<p align="center">
  <em>Figure 7: American Sign Language (ASL) representation of the letter D</em>
</p>
<br>
<br>
<p align="center">
  <img src="website pictures and gif/asl - letter f .png" alt="ASL Letter F" width="600">
</p>
<p align="center">
  <em>Figure 8: American Sign Language (ASL) representation of the letter F</em>
</p>
<br>
<br>
<p align="center">
  <img src="website pictures and gif/asl - letter o.png" alt="ASL Letter O" width="600">
</p>
<p align="center">
  <em>Figure 9: American Sign Language (ASL) representation of the letter O</em>
</p>








