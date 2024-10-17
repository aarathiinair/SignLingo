# SignLingo
SignLingo is an innovative software project designed to bridge communication gaps between users of Indian Sign Language (ISL) and American Sign Language (ASL). Input a sign and it translates between these two widely used sign languages in real-time.

[Insert GIF or video demonstration here, similar to the Cinecomic example]

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

> Read the project report for detailed explanations

## Pre-requisites
- Python 3.x
- pip (Python package installer)
- MySQL server
- ASL and ISL image files for each letter

## Running the project
- Ensure you have the necessary ASL and ISL image files in the correct directory
- Update MySQL connection details in `app.py` and `add_imgs_to_db.py` if necessary
- Populate the database: `python add_imgs_to_db.py`
- Run the flask server: `python app.py`
- Open the localhost link on your browser (Eg: `http://localhost:5001` or `http://127.0.0.1:5001`)

## Some more examples
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
