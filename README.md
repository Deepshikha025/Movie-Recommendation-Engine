# Movie-Recommendation-Engine
This is a movie recommendation engine which is content based.


# Dataset
Dataset is taken from kaggle and can be downloaded from the link given below.
https://www.kaggle.com/datasets/carolzhangdc/imdb-5000-movie-dataset


# Features of Recommendation Engine
* Simple Responsive User Interface
* Movie Poster
* IMDB Ratings


# How to Run Project?
* Clone my Repository and make sure that if you change folder location, do change it in movie-web-Copy2.ipynb(jupyter notebook) file, App.py and Classifier.py file.
* Open CMD in working directory.
* Run the command.
  **pip install -r requirements.txt**
* In Streamlit-Web Application, **App.py** is the main file.
* For running the app, run the command in CMD or in the terminall of streamlit.
  **streamlit run App.py**
 * For dataprocessing **movie-web-Copy2.ipynb** file is used.
 * Algorithm used is KNN(euclidean distance), which is contained in **Classifier.py** file.


 **OR**
 * Download the dataset from the link given in GitHub Readme file.
 * Install Anaconda Navigator and make sure that you run required commands for its working in the system.
 * Through Anaconda Navigator, launch jupyter notebook, also download jupyter notebook and run required commands for your system. After this run my movie-web-            Copy2.ipynb file.
 * Install pycharm and required libraries. Install streamlit using command: **pip install streamlit**, in terminal of pycharm.
 * For the libraries required in the project, run command: **pip install -r requirements.txt** in terminal of pycharm.
 * For running my file **App.py**, run command : **streamlit run App.py**, in terminal of pycharm. This will open the project in localhost.
 * Make sure the locations of file would be changed in your system, so change them accordingly in **App.py, Classifier.py** and **movie-web-Copy2.ipynb** file.


