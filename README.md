# Register assisted aggregation for Visual Place Recognition
Xuan Yu, Zhenyong Fu


we propose a new method, which uses Registers to assist in removing irrelevant information from image representations in VPR tasks while preserving valid information, called RegVPR. Our method introduces registers during the feature aggregation process and uses a Transformer Encoder containing self-attention mechanism to reassign feature weights on the original image tokens and the local descriptor sequence after register concatenation. These registers can effectively capture these tokens containing a large amount of background information and discard them without compromising the quality of descriptor representation. We use pre-trained DINOv2 as our backbone and introduce some lightweight adapters to fine-tune the pre-trained backbone, thus enabling the pre-trained foundation model to seamlessly adapt to VPR tasks.
![Introduction](img/heatmap_introduction.png)
