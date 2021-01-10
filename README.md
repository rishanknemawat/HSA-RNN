# HSA-RNN
Although video summarization has achieved great success in recent years, few approaches have realized the influence of video structure on the summarization results. As
we know, the video data follow a hierarchical structure, i.e., a video is composed of shots, and a shot is composed of several frames. Generally, shots provide the activity-level
information for people to understand the video content. While few existing summarization approaches pay attention to the shot segmentation procedure. They generate shots by
some trivial strategies, such as fixed length segmentation, which may destroy the underlying hierarchical structure of video data and further reduce the quality of generated sum-
maries. To address this problem, we propose a structure-adaptive video summarization approach that produces shot segmentation into a Hierarchical
Structure-Adaptive RNN, denoted as HSA-RNN. We evaluate the proposed approach on popular dataset, TVsum. 

We have developed a deep learning model using transfer learning to extract the features from the video and also created generators to fit larger datasets.

DataSet Used - TVSum (Test Dataset: 5 Videos, 25044 Frames)
Used VGG Pretrained model for feature extraction, with Bidirectional LSTM Layers and Attention Layers
