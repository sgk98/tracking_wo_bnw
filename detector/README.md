# Modifications to the Faster-RCNN Training

The models are available here: https://drive.google.com/drive/folders/1jxgMNx2y6b0ZeCjftUpwsZ2YhjfGTBoN?usp=sharing
The ```original``` directory has the original model, the ```improved``` directory has the improved models and the ```combined``` directory has the models trained on both MOT17 and MOT20 datasets.

 


```orig_frcnn.py``` has the original training script and parameters.
```combined_frcnn.py``` has the training on the combined data.
```frcnn.py``` was used to train the improved model.
```eval.py``` was used to compute the Average Precision(AP) and other metrics.


## Usage
To evaluate a model, use ```python3 eval.py <path_to_model>``` This assumes the MOT20Det/MOT17Det is kept in the same directory. This can be changed in line 359.


## Training
To train the detector, place the MOT17Det/MOT20Det dataset in the current directory. To train on the combined data, create a directory named ```combined``` which has a train sub-directory containing both the MOT17 and MOT20 train sequences.

A directory to store the checkpoints also needs to be made.
The command ```python3 <file_name>``` would work to train. 


