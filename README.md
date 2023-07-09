# Speech-Emotion-Recognition
SPEECH EMOTION RECOGNITION,is a ML based project.

OBJECTIVE : To build a model to recognize emotion from speech using the librosa and sklearn libraries and the RAVDESS dataset.

Dataset link: https://www.kaggle.com/datasets/dejolilandry/ravdess

STEPS TO EXECUTE THE PROJECT CODE:

1.Download the dataset from above link and place it in google drive.

2.Create a google colaboratory for the project(both dataset and colab notebook should be under same mail).

3.Copy the contents from copy_final_ser.py into cells of colab.

4.After running first cell ,drive will be mounted i.e.,drive files will be appeared to use.

5.Left side of colab there is file upload option , click that and upload (app.py and utils.py).

6.Under load_data function give your dataset url (i.e.,left side lclick drive and then dataset and then ravdess and then actor -> click 3 dots and from there copy path).

7.Run all the cells.

8.After running last cell , 3 urls will be appeared, click "your url".Then "click to continue" button in tunnel website and then slowly streamlit will be loaded.

9.Give any audio file of wav type with less than 200 mb file size -> click predict-> emotion will be predicted.

NOTE :

Copy_final_ser.py is build based on MLP classifier.

Excluding Sreamlit part, Same process is also done with SVM.py then accuarcy of both models will be compared.

MLP classifier gives best accuracy , so streamlit part is build with MLP model.

Likewise any other suitable model is constructed and compare their accuracies and select the best model from them.Train the model and get accuarcy
