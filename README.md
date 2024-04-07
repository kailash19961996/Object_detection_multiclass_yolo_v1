# Multiclass Object Detection with YOLO v1 from Scratch

## Introduction
In this project, I have developed a  multiclass object detection model using the YOLO v1 (You Only Look Once) architecture from scratch. The YOLO model is a popular and efficient object detection algorithm that can simultaneously detect and classify multiple objects within an image.

## Key Features
- **Custom YOLO v1 Implementation**: I have implemented the entire YOLO v1 model, including the feature extraction backbone, grid-based detection, and non-maximum suppression, without relying on any pre-built object detection frameworks.
- **Multiclass Object Detection**: The model is trained to detect and classify multiple object types within a single image, making it a versatile tool for a wide range of computer vision applications.

## Challenges Addressed
1. **Algorithm Complexity**: Handling the intricate details of the YOLO v1 algorithm, such as the grid-based object prediction, loss function optimization, and non-maximum suppression was a significant challenge.
2. **Data Preprocessing**: Preparing the dataset for training the model, including image resizing, normalization, and bounding box labeling, required careful attention to ensure high-quality input data.
3. **Model Optimization**: Tuning the hyperparameters of the model, such as learning rate, batch size, and network architecture, to achieve the best performance on the object detection task.
4. **Loss function


## Future Improvements
1. **Exploring Newer YOLO Versions**: Investigating the newer iterations of the YOLO architecture, such as YOLO v3 or YOLO v5, to further enhance the model's performance and capabilities.
2. **Incorporating Transfer Learning**: Leveraging pre-trained models or feature extractors to improve the model's learning efficiency and generalization.
3. **Real-time Inference**: Optimizing the model for real-time object detection, enabling its use in applications that require low-latency responses, such as autonomous vehicles or surveillance systems.
4. **Expanding Dataset and Classes**: Expanding the dataset to include a wider range of object classes, improving the model's versatility and real-world applicability.

## Acknowledgments
I would like to acknowledge the research and development efforts of the YOLO team, whose work has been instrumental in advancing the field of object detection. Additionally, I'm grateful for the open-source tools and libraries that have made this project possible, including PyTorch, Streamlit, and the various computer vision resources available.

