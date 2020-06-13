# Modifications to the Faster-RCNN Training

The models are available here: https://drive.google.com/drive/folders/1jxgMNx2y6b0ZeCjftUpwsZ2YhjfGTBoN?usp=sharing
The ```original``` directory has the original model, the ```improved``` directory has the improved models and the ```combined``` directory has the models trained on both MOT17 and MOT20 datasets.

```orig_frcnn.py``` has the original training script and parameters.
```combined_frcnn.py``` has the training on the combined data.
```frcnn.py``` was used to train the improved model.
```eval.py``` was used to compute the Average Precision(AP) and other metrics.

