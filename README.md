# BrainTumorSegmentation---UNet-java-

Dataset obtained from https://www.kaggle.com/mateuszbuda/lgg-mri-segmentation.
Randomly selected 550 data for testing, the rest are used for training. All images are seperated into inputs and Mask folder for both testing and training. Inputs and Mask should have the same label corresponding to each other.

BraintumorUnet.java : Pretrain model

BraintumorDatasetIterator.java : Iterator

BraintumorLoad.java : Load the trained model

BrainTumor.zip : Trained model. Download here shorturl.at/axGIM

Train.png : Overview of the model's training

Media1 : Recorded while running the trained model

Result
Mean IOU : 0.6853

Limited by time and laptop hardware, unable to use CUDA due to limited memory, run on stocked GPU Intel(R) HD Graphics 4600
