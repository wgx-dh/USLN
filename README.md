# USLN
USLN: A statistically guided lightweight network for underwater image enhancement via dual-statistic white balance and multi-color space stretch
Implementation: PyTorch
## overview

## train and test
if you want to train the model:\
1, put your datasets into corresponding folders ("images_train", "labels_train", "images_val", "labels_val")\
2, run train.py\
3, the checkpoints will be saved in "logs"

if you want to test the model:\
1, put your datasets into "images_test"\
2, run test.py (load model checkpoints from "logs" first)\
3, the result will be saved in "pred"
