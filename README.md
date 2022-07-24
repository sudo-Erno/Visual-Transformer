![]


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