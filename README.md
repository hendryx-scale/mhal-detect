# M-HalDetect
A dataset used for detecting and preventing hallucinations in multimodal models.
[Original paper](https://arxiv.org/abs/2308.06394)

Each sample contains the exact question asked to the multimodal model, with the coco 2014 validation image id that was used. The annotations for each sample consists of a list of segments, containing start and end indices, with a string representing the spanned text, and a class label.
