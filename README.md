# Sign-Language-recognition-using-Mediapipe
This project uses Hand gesture recognition with MediaPipe Model Maker to effectively recognize sign language from livestream. 
How to Run
There are 2 steps to running the project.
1. Training the Model
1. In the training_task_file.ipynb file, import dependencies, and the datasets from
kaggle.
2. Unzip the datasets
3. Go into the files folder and change the name for the ‘nothing’ classes in both test and
train folders to ‘none’ (The code won’t work otherwise)
4. Create and fit the gesture_recognizer model on the data by running the cells
5. Download the gesture_recognizer.task file and save it to your computer.
2. Using the Model
1. In the sign_language.ipynb file , import dependencies
2. Upload the gesture_recognizer task into the runtime (since the model takes time to
train, we attached our trained model file with our submission).
3. Run the Colab code snippets for webcam access and all other cells.
4. In the last cell , the webcam will open.
5. In the webcam, start signing letters from ASL and the model will write our the output
from the gesture_recognizer.
6. The predicted output for the letter will be in the ‘category_name’ part of our printed
statement.
