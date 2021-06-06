# Mask_Detector
***
## Transfer learning Using RESNET MODEL
#### Implementation of Transfer Learning for training model:
- Only last layer is trained and top layer is included while training the model.
- Model is trained on **20 EPOCHS**.
- Optimizer used is **Adam** and Learning Rate is **0.001**.
- Loss function used is **categorical_crossentropy**.

#### Details of Dataset:
- Dataset is classified into two categories (with_mask and without_mask).
- Number of images in Dataset:

|with_mask |without_mask |
|--------- |------------ |
|  1915	   |   1918      |

- Batch size for training and testing is **30**.
- Images are first preprocessed using resnet algorithm and resized to **(224,224)** to feed it into RSENET50 model.

****

## How to run the code?
- Download any available dataset and resize it to (224,224,3).
- After that, execute **tl.ipynb** file.
- And then execute **tl2.ipynb** file.
