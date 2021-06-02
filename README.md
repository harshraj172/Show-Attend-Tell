# Show-Attend-Tell
The notebook attached describes the implementation of a breakthrough paper in image captioning "Show Attend Tell".

1.Used attention-based model, which enables us to see what parts of the image the model focuses on as it generates a caption.

2.The dataset used is the MS COCO dataset which contains over 82,000 images, each of which has at least 5 different caption annotations. 

2.Notebook downloads the MS-COCO dataset, preprocesses and caches a subset of images using **Inception V3**, trains an encoder-decoder model, and generates captions on new images using the trained model.
