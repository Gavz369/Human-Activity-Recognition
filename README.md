# Activity Recognition using ConvLSTM
Jupyter Notebook implementation of Human Activity Recognition using ConvLSTM 

## Dataset Used
The dataset used in the training process is the UCF50 - Action Recognition Data Set. Dataset can be downloaded from [this link](https://www.crcv.ucf.edu/data/UCF50.php)</br>
The dataset contains:
- 50 Action Categories
- 25 Groups of Videos per Action Category
- 133 Average Videos per Action Category
- 199 Average Number of Frames per Video
- 320 Average Frames Width per Video
- 240 Average Frames Height per Video
- 26 Average Frames Per Seconds per Video


## PreProcessing
- `Sequence length = 20` has been selected to be feeded into both the networks (ConvLSTM).
- `Image_width, Image_height = 64, 64` set for the input sequences/frames to be feeded into the networks
- `Training Data = 60%`, `Validation Data = 20%`, `Testing Data = 20%` has been set.


## ConvLSTM Model Performance
After training on `20 epochs` early stopping CallBack was triggered. `Test Accuracy = 70%`, and `Test Loss = 70%`


 - The best weights are stored in `Models` folder

