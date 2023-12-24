# xView Dataset Image and Label Extraction

The primary aim of this repository is simplify the extraction of images and their corresponding labels from the [xView dataset](http://xviewdataset.org/), focusing on a specific class, such as aircraft, for AI experiments.  🚀 ✈️ 

[The xView dataset](http://xviewdataset.org/), owned by the [Pentagon's Defense Innovation Unit](https://www.diu.mil/), offers a wealth of aerial imagery. This repository provides a streamlined process for working with this data. By utilizing the included Colab notebook, users can efficiently extract relevant images and labels for their specific use cases.  Moreover, to enhance the exploration of the dataset, an interactive map showcasing the spatial distribution of sampled images is available through the [Google Drive link](https://drive.google.com/drive/folders/1NWVTR3cepFSr98cB202ncT_qcZjwCwSG?usp=sharing). This map, presented as an HTML file, visually represents the geographic prevalence of different objects, offering valuable insights into the dataset's distribution. People interested in this map can add their own vector data in GeoJSON format to the map and develop their own maps according to their purposes.💡 🚀 (See below)

![image](https://github.com/dilsadunsal/xview_du/assets/77750296/30810b73-ca03-4213-9d3c-a06fd80acd30)




[This link](https://dilsadunsal.github.io/xview_du/) also includes a map displaying the distribution of image frames from which object samples were taken. (See below)

![image](https://github.com/dilsadunsal/xview_du/assets/77750296/a2618c6d-dabd-44cd-9ee9-19f3c51c12b2)


# Repository Purpose and Functionality

**Extraction:** The repository offers a specialized Colab notebook designed to streamline the extraction process. Users can obtain images and corresponding labels for a specific class, simplifying the data preparation phase for various computer vision tasks.💡

**Compatibility:** The provided codes are tailored to seamlessly work with the xView dataset. While the example centers around aircraft extraction, the codes are adaptable for other classes within the dataset.

**Interactive Maps:** Explore the [Google Drive link](https://drive.google.com/drive/folders/1NWVTR3cepFSr98cB202ncT_qcZjwCwSG?usp=sharing) provided in this repository to access an interactive map showcasing the distribution of images sampled from the xView dataset. This map, available as an HTML file, provides a visual representation of the dataset's spatial distribution, aiding in understanding the geographic prevalence of different objects. [The other map included in this link](https://dilsadunsal.github.io/xview_du/) shows the distribution roughly through the image frames.

# Notebook Overview

The Colab notebook included in this repository is a comprehensive tool with a well-defined structure for ease of use and understanding. The notebook is organized as follows:

**1. Mounting Google Drive:** The notebook guides users through the process of mounting their Google Drive, a crucial step for accessing and storing data seamlessly, especially when working with cloud-based resources.

**2. Code Structure**: The subsequent sections of the notebook systematically approach the image and label extraction process. Each code snippet is accompanied by explanatory comments, facilitating user comprehension and adaptation for different use cases.

**3. Label Format Conversion:** A key feature of the notebook is its ability to convert labels from the geojson format commonly used in the xView dataset into the YOLO.txt format. This conversion is crucial for making the labels readily usable for YOLO (You Only Look Once) experiments, a popular object detection algorithm.

**4. Cloud-Based Testing:** The notebook includes sections specifically designed for testing code snippets with cloud-based data, enhancing flexibility and validation capabilities.

# Citations and Acknowledgments

If you incorporate the xView dataset into your research or development projects, kindly reference the following paper:
[D. Lam, R. Kuzma, K. McGee, S. Dooley, M. Laielli, M. Klaric, Y. Bulatov, and B. McCord, ''XView: Objects in context in overhead imagery,'' 2018, arXiv:1802.07856.](https://arxiv.org/pdf/1802.07856.pdf)

Deepest gratitude to the United States Defense Innovation Unit (DIU) and the creators of the xView dataset for their invaluable contribution to the computer vision research community. To learn more about the xView dataset and its originators, please visit the following link: https://www.diu.mil/ai-xview-challenge

Thanks to [Ultralytics](https://www.ultralytics.com/) for generously sharing their documents and codes related to xView: https://docs.ultralytics.com/datasets/detect/xview/
