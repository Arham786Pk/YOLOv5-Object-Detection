📌 YOLOv5 Object Detection Project – Complete Description
This project is designed to automate object detection using YOLOv5, a state-of-the-art deep learning model. It downloads a sample image, loads a pre-trained model, detects objects, and visualizes the results.

📌 How the Project Works
Downloading a Sample Image

The program checks if a sample image is available; if not, it downloads an image of Zinedine Zidane playing football.
Loading the YOLOv5 Model

Uses Torch Hub to automatically download and load YOLOv5 Small (yolov5s).
The model is pre-trained on the COCO dataset (detects 80 object classes).
Performing Object Detection

Reads the image and converts it into RGB format (since OpenCV loads images in BGR).
Runs the YOLOv5 model to detect objects, classify them, and draw bounding boxes.
Displays the detected objects with labels.
Displaying & Printing Detection Results

The program shows the processed image with bounding boxes.
Prints details such as object name, confidence score, and bounding box coordinates.
📌 Expected Output
The detected objects are highlighted with bounding boxes on the image.
The console displays a table of detected objects, including:
Object Name (e.g., "person", "soccer ball")
Confidence Score (e.g., 98% certain it's a person)
Bounding Box Coordinates
📌 Key Features
✅ Uses a pre-trained YOLOv5 model (no need for training)
✅ Automatically downloads required files
✅ Fast object detection with bounding boxes & confidence scores
✅ Easily customizable for different images or real-time detection

📌 Possible Enhancements
Use custom images instead of the sample image.
Save the processed image with detected objects.
Implement real-time detection using a webcam.
Train YOLOv5 on custom datasets for specific object detection.
