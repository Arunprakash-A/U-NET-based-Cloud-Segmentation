# U-NET-based-Cloud-Segmentation
 * FCNN (U-NET) architecture is trained (Just for an epoch) to segment a cloud region from remotely sensed optical images.<br>
 * Data reading, formatting etc., have been taken care of for you to execute the notebook smoothly on Colab <br>
 * If you have a dedicated compute resource, you can run it for more number of epochs, modify the architecture...
 * I hope this notebook adds some clarity on semantic segmentation by providing a hands-on.

Details of the dataset are at : https://arxiv.org/ftp/arxiv/papers/1810/1810.05801.pdf

## Sample Input with the respective mask
![alt text](https://github.com/Arunprakash-A/U-NET-based-Cloud-Segmentation/blob/main/images/img_mask.png "Sample Image")

## Segmented Cloud Region (Not accurate enough, though)
![alt text](https://github.com/Arunprakash-A/U-NET-based-Cloud-Segmentation/blob/main/images/img_mask_pred.png "Predicted Cloud region")

## Segmentation on a random image from Google.
![alt text](https://github.com/Arunprakash-A/U-NET-based-Cloud-Segmentation/blob/main/images/unseen.png "Predicted Cloud region")
