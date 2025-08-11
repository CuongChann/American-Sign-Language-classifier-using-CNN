# American-Sign-Language-Alphabet-classifier-using-CNN
This notebook is my personal project in Deep Learning with Pytorch. It experimented on 3 models for a multi-class computer vision classification task and overviewed the results using TensorBoard. I used transfer learning to apply pre-trained backbones like Resnet18 and EfficientNetB0 for this customized task.

The dataset used is the American Sign Language Alphabet dataset: https://www.kaggle.com/datasets/grassknoted/asl-alphabet/data

The actual training time can get as long as 1 hour (for all 3 models). In order to use the trained parameter and output prediction instantly, you will need to:

1. Upload the file model_1.pth to your workspace
2. Copy the file path and paste to "model_best.load_state_dict" function in the 4th cell from bottom up
3. Upload the image you want to test (with cleared background)
4. Copy the image path and paste to "Image.open" function in the 3rd cell from bottom up
5. Run the last cell

