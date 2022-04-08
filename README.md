# Object-Detection-with-Deep-Learning-models
- This repo examines the use of deep neural networks in object recognition. Machines that rely on computer vision are able to accurately identify and classify objects through deep learning by training models using images and videos.
- In order to build the deep learning models I used the pre-defined functions for YOLOv2 model in Keras, link for the YOLOv2 model is here: https://github.com/experiencor/keras-yolo2
- The implementation of the YOLOv2 model can be found in the code above, please note you also require to download the associated model weights which can be found at this link: https://drive.google.com/file/d/14VAjqZDnAIfsUy_ZxmUyhUDQGTfiDmbs/view
- I wrote a medium article on this topic:https://khalidmasaid.medium.com/object-detection-with-deep-learning-de1df7d48318

# Model output
- If I input the following picture into the YOLO model it must detect the pedestrians, bus, traffic lights and cars in background.
<img width="527" alt="image" src="https://user-images.githubusercontent.com/103283892/162532856-dc54fe8c-b4cb-4b2d-9db3-dea9071c5140.png">
- As expected, the model was able to accurately detect multiple objects in the sample image.
<img width="511" alt="image" src="https://user-images.githubusercontent.com/103283892/162533290-4a3befa1-b2f4-4cdd-9705-a4aa45976bb2.png">
