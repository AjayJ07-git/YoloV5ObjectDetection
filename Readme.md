# YOLOv5 Image Object Detection

This repository contains a Jupyter Notebook for performing object detection using the YOLOv5 model. YOLOv5 is a family of object detection architectures and models pretrained on the COCO dataset, allowing for fast and accurate detection of objects in images.

## Getting Started

### Prerequisites

Before you can run the code in this repository, ensure that you have the following installed on your system:

- Python 3.8 or higher
- pip (Python package installer)
- Visual Studio with Python support

### Installation

1. **Clone the YOLOv5 repository**  
   The first step is to clone the YOLOv5 GitHub repository, which contains the necessary code and pre-trained models for YOLOv5.

   ```bash
   git clone https://github.com/ultralytics/yolov5.git
   ```

2. **Navigate to the YOLOv5 directory**  
   Change your current directory to the cloned repository.

   ```bash
   cd yolov5
   ```

3. **Install the required dependencies**  
   Install the dependencies required to run the YOLOv5 model.

   ```bash
   pip install -r requirements.txt
   ```

### Usage in Visual Studio

1. **Open the Project**  
   - Open Visual Studio and go to `File` > `Open` > `Folder...`.
   - Select the `yolov5` directory you cloned earlier.

2. **Run the Jupyter Notebook**  
   - In Visual Studio, navigate to the `yolov5imgobjdet.ipynb` file.
   - Open the notebook, and you will see an interactive interface where you can execute cells.
   - Follow the instructions in the notebook to perform object detection on images.

### Directory Structure

- `yolov5imgobjdet.ipynb`: The main Jupyter Notebook for performing object detection.
- `data/`: Contains sample images and other data files used in the notebook.
- `models/`: Directory where you can store the YOLOv5 model weights.
- `runs/detect/exp`: Directory where the result are stored.

### Notes

- The notebook is configured to work with the YOLOv5 model, and you may need to modify paths or configurations based on your specific environment.
- Ensure that your system's GPU has sufficient memory (4GB or more) if you plan to use GPU acceleration.

### Acknowledgments

- [YOLOv5](https://github.com/ultralytics/yolov5) by Ultralytics is a state-of-the-art object detection model that has been widely adopted for various applications.

### Contributing

- We welcome contributions to enhance this project. Please fork the repository and create a pull request with your changes. Ensure your code follows the project's coding standards and includes appropriate tests.

### Contact

- For any questions or feedback, please reach out to [Ajay] at [ajayjnitt@gmail.com].