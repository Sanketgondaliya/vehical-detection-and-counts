
# Vehicle Detection and Counting Web Application

## Overview

This web application performs vehicle detection and counting on uploaded images using the Roboflow Serverless API. It provides visual detection results with bounding boxes, confidence metrics, class-wise vehicle counts, and interactive image inspection tools. The application is designed for demonstration, analysis, and integration into traffic monitoring or computer vision workflows.

---

## Key Capabilities

- Image upload via file selection or drag-and-drop
- Vehicle detection and counting using a trained Roboflow model
- Bounding box visualization on detected vehicles
- Class-wise vehicle count breakdown
- Average confidence score calculation
- Processing time measurement
- Image zoom, pan, and fullscreen inspection
- API key visibility control
- Responsive layout for desktop and mobile devices

---

## Technology Stack

### Frontend
- HTML5
- CSS3
- Vanilla JavaScript

### Machine Learning Backend
- Custom detection workflow: `detect-count-and-visualize`



## Application Flow

1. User uploads an image containing vehicles.
2. The image is converted to Base64 format on the client.
3. The image is sent to the Roboflow Serverless API.
4. The API returns detection metadata and a processed image.
5. The application renders detection results and analytics.

---

## Setup and Usage

### Prerequisites
- Modern web browser (Chrome, Edge, Firefox)
- Active internet connection
- Valid Roboflow API key

### Running the Application
1. Clone the repository: git clone https://github.com/sanketgondaliya/vehicle-detection-counting.git

###  Application URL: https://sanketgondaliya.github.io/vehicle-detection-counting


### Security Note

API keys should not be committed to public repositories. For production deployments, route API calls through a secure backend or environment-based configuration.

---

## Detection Controls

* **Confidence Threshold**
  Sets the minimum confidence required for detections.

* **Overlap Threshold**
  Controls suppression of overlapping bounding boxes.

---

## Output Details

* Total vehicle count
* Average detection confidence
* Vehicle class distribution
* Bounding box visualization
* Detection metadata including position and dimensions

---

## Limitations

* Performance depends on image size and network latency
* Detection accuracy depends on model training quality
* Client-side API usage is not suitable for unrestricted public deployment

---

## Potential Use Cases

* Traffic analysis and monitoring
* Smart city demonstrations
* Computer vision model evaluation
* Academic and industrial proofs of concept

---

## Future Enhancements

* Video and real-time stream processing
* Backend service for secure API access
* Result export (CSV, JSON)
* Integration with analytics dashboards



## Acknowledgements

* Roboflow
* Font Awesome
* Open-source community



If you want, I can now:
- Strip it down further (enterprise-minimal)
- Add compliance/security notes
- Customize it for a **client proposal** or **internal company repo**
- Align wording with **ISO / smart city / traffic systems**


