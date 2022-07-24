Visual Transformer (ViT) made from scratch with PyTorch.

The model was trained on the MNIST dataset.

# Hyperparameters
- HEIGHT = 32
- WIDTH = 32
- CHANNELS = 1
- BATCH_SIZE = 32
- PATCHES_DIM = 16
- EMBEDDING_DIM = 512
- NUM_CLASSES = 10
- NHEADS = 8
- DROPOUT_P = 0.1
- EPOCHS = 25
- LEARNING_RATE = 1e-3
- FORWARD_EXPANSION = 4
- MLP_EXPANSION = 3
- MOMENTUM = 0.9
- NUM_LAYERS = 8
- DEVICE = "cuda" (In my case GTX 750 Ti)

# Performance of the model
![](https://github.com/sudo-Erno/Visual-Transformer/blob/master/media/Performance.png)

# Output
![](https://github.com/sudo-Erno/Visual-Transformer/blob/master/media/Predictions.png)

# RESOURCES

- AN IMAGE IS WORTH 16X16 WORDS: https://arxiv.org/pdf/2010.11929.pdf

- Attention Is All You Need: https://arxiv.org/pdf/1706.03762.pdf

- Paper Explained- Vision Transformers (Bye Bye Convolutions?): https://medium.com/analytics-vidhya/vision-transformers-bye-bye-convolutions-e929d022e4ab

- Explanation of the input layer: https://medium.datadriveninvestor.com/coding-the-vision-transformer-in-pytorch-part-1-birds-eye-view-1c0a79d8732e

- Code and explanation #1: https://github.com/jankrepl/mildlyoverfitted/blob/master/github_adventures/vision_transformer/custom.py

- Code and explanation #2: https://theaisummer.com/vision-transformer/

- Good repo: https://github.com/cmhungsteve/Awesome-Transformer-Attention#vision-transformer

#### TODO List:
- [x] Change images_shape parameter since it's (50, 32, 32, 1) to (batch, 32, 32, 1).
- [x] Check if there are the exact number of images in a batch. If not, work on it.
- [x] Move the model to CUDA.
- [x] Create measurement for accuracy.
- [x] Create evaluation function.
- [x] Add dropouts layers.
- [ ] Make the model accept differents batch size.