# Object Detection with YOLOS
---
<center>
  <img src="https://github.com/Zaheer-10/Object-Detection/blob/main/Resources/YOLO__03.png" alt="Banner" >
</center>

Object detection is a computer vision technique that identifies and classifies a particular object in a particular setting. The main goal of object detection is to scan digital images or real-life scenarios to locate instances of every object, separate them, and analyze their necessary features for real-time predictions. Object detection algorithms typically leverage machine learning or deep learning to produce meaningful results. Object detection is used in various domains, such as image annotation, vehicle counting, activity recognition, face detection, face recognition, video object co-segmentation, etc.

- In this project, I aim to demonstrate how to use YOLOS models for object detection on  images  using Gradio, a Python library that allows us to build and share web applications for our machine learning models or data science workflows.

- I also used some predefined YOLOS models from the Hugging Face hub as our data sources. We use `gr.components.Dropdown()` to create a dropdown component that can let users choose from different YOLOS models available on the hub.
- The models used are:

  - `yolos-tiny`
  - ` yolos-small`
  - ` yolos-base`
   - `yolos-small-300`
   - `yolos-small-dwr`
- These models have different sizes and performance trade-offs. You can find more details about these models on their respective pages on the hub.
---
## Installation
- To run this project, you need to install some dependencies:

     - `Python 3`
     - `PyTorch`
    - ` Transformers`
    -  `Gradio`
     - `OpenCV`
    -  `Numpy`

- You can install these dependencies using pip:

    `pip install -r requirements.txt`

---
## Usage
- To run this project, you need to execute the app.py script:
      `python main.py`

---
## Examples
- Here are some examples of object detection using different YOLOS models and inputs:
<center>
  <img src="https://github.com/Zaheer-10/Object-Detection/blob/main/Resources/YOLO_001.png" alt="Girl in a jacket" >
  <br>
  <img src="https://github.com/Zaheer-10/Object-Detection/blob/main/Resources/YOLO_002.png" alt="Girl in a jacket" >
</center>

The application can be accessed here: [MyApp](https://huggingface.co/spaces/soulofmercara/Object-Detection-with-YOLO)

---
## Report
- The project report is available [here](https://github.com/Zaheer-10/Object-Detection/blob/main/Resources/Object_detection_Project_Report.pdf). It provides a detailed explanation of the methodologies used, results obtained, and conclusions drawn from this project.

---

## Future Work

- [ ] Adding more features and functionalities to our web application, such as downloading, sharing, or editing the results.
- [ ] Evaluating the performance and quality of our web application using metrics and feedback.
- [ ] Adding more YOLOS models from the Hugging Face hub or other sources.
- [ ] Adding more input and output components from Gradio or other libraries.

---
## License 
- This project is licensed under the MIT License. 📝
