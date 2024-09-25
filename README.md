# KneeXpert: YOLO-based Detection of Knee Osteoarthritis

This project focuses on detecting knee osteoarthritis using YOLOv5 for object detection and TensorFlow/Keras for further processing and classification. The system is designed to automate the detection of osteoarthritis by analyzing knee X-ray images.

## Requirements

- Python 3.x
- YOLOv5
- TensorFlow 2.x
- PyTorch
- PIL
- Matplotlib

Install the necessary dependencies

## YOLOv5 Inference
You can run inference using a pretrained YOLOv5 model to detect osteoarthritis from knee X-ray images. Replace the `path` in the code to point to your trained YOLOv5 model weights.

## Output
Bounding boxes will be drawn on the detected knee regions, and cropped images of detected regions will be saved in the output_images/ directory. The TensorFlow/Keras model can further classify the images based on your training setup.
