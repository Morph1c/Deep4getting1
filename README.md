# Deep4getting1
First challenge for the course of Artificial Neural Network and Deep Learning.

History of model accuracy on test set:
<br>
-CNNvanilla, see CNNvanilla.ipynb, error on test set: 0.63
<br>
-Resnet with fine-tuning (128 layers), error on test set: 0.7
<br>
-ConvNextBase fine-tuning(64 layers), error on test set 0.86
<br>
-ConvNextBase fine-tuning(64 layers), error on test set 0.86 differ from the previous on the data augmentattion part since we add brightness [0.5, 1.5] and noise
<br>
-Contrastive Learning (base model: ConvNextBase), erro on test set ?
<br>
-ConvNextBase fine-tuning(32 layers), error on test set 0.88
<br>
-VGG16 fine-tuning(all layers), error on test set 0.72
<br>


For augmentatiom: intro_code_tensor.ipynb for following the same preprocessing
<br<
For training pipeline: convnext.ipynb

