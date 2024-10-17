# SignLingo
SignLingo is an innovative software project designed to bridge communication gaps between users of Indian Sign Language (ISL) and American Sign Language (ASL). Input a sign and it translates between these two widely used sign languages in real-time.
## Methodology
Our project consists of the following core modules:
1. **Image Processing**
    - Processes input images of hand signs for ASL and ISL
2. **Machine Learning Models**
    - SVM: Classifies hand signs with high accuracy
    - GridSearchCV: Fine-tunes our model for optimal performance
    - StandardScaler: Normalizes data for consistent sign recognition
3. **Database Management**
    - Stores and retrieves sign language images for each letter
4. **Real-time Translation**
    - Provides instant translation between ASL and ISL
5. **Web Interface**
    - Offers a user-friendly interface for seamless interaction
## Pre-requisites
- Python 3.x
- pip (Python package installer)
- MySQL server
- ASL and ISL image files for each letter
## How to Run SignLingo
Follow these steps to set up and run SignLingo on your local machine:
### Prerequisites:
* Python 3.x 
* pip (Python package installer)
* MySQL server
* ASL and ISL image files for each letter
### Populate the Database:
1. Place your ASL and ISL image files in a known directory.
2. The script assumes they are in C:/Program Files/MySQL/MySQL Server 8.0/Uploads/.
3. Update the image file paths in the database population script if your images are stored elsewhere.
4. Run the database population script:
   ```
   python add_imgs_to_db.py
   ```
   This script will insert the images for each letter into the translation_table.
### Configuration
Open app.py and add_imgs_to_db to update the MySQL connection details if necessary:
   ```python
   host="localhost",
   user="root",
   password="ArteryNoir#5",
   database="aarathi"
   ```
### Running the Application
1. Start the main application:
   ```
   python app.py
   ```
2. Open your web browser and navigate to http://localhost:5001 or http://127.0.0.1:5001 to access the SignLingo interface.
<p align="center">
  <img src="website pictures and gif/front page.gif" alt="SignLingo Front Page" width="600">
</p>
<p align="center">
  <em>Front page of the SignLingo application</em>
</p>
<br>
<br>
<p align="center">
  <img src="website pictures and gif/1080.gif" alt="SignLingo Demo GIF" width="600">
</p>
<p align="center">
  <em>Demonstration of SignLingo application in action</em>
</p>
