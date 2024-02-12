# Vehicle-trajectory-prediction
Vehicle trajectory prediction involves using deep sort and YOLO for object detection to track a car's coordinates in video. These coordinates, along with speed data, are stored in a database. This dataset is then used to train a model, often using LSTM, to predict future vehicle coordinates based on historical data. 

To predict the future coordinates of the vehicles, the dataset is then utilized to train a model, often employing methods such as Long Short-Term Memory (LSTM) networks. LSTM is a type of recurrent neural network that is well-suited for sequence prediction tasks, making it suitable for predicting the future trajectory of vehicles based on the historical coordinates and speeds in the dataset.

The process involves extracting, tracking, and storing the coordinates and speeds of vehicles from videos, and then using this data to train a model that can predict future coordinates based on the historical patterns observed in the dataset.

**The code to find coordinates is available in a zip file with the name predict.py along with the video.**\


**Code to transform the dataset** : https://colab.research.google.com/drive/1XUchBZ2VPWT8da4lHNpywIIl5fYUh9tG#scrollTo=lICOW-LxnG0v



**NOTE :  test_excel.xlsx is transform to xy_test.xlsc using above code both are present in zip file attached below.**


**Trajectory prediction code** :  https://colab.research.google.com/drive/1hAU68DDPBhOMvXJhE-N1cTX9CRWhXeah?usp=sharing
