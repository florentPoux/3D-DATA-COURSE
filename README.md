# 3D-DATA-COURSE
Geospatial 3D Data Processing Courses for Digital Twins. 
ITC, University of Twente.

# 3D Data Processing Open Course

![3D Data Processing Logo](https://1348661504.rsc.cdn77.org/.uc/i6e7f12dd0102675d8401aa63f60105b60425f1c734e90701c3ee02000080/itc-langezijds-34.jpg)

Welcome to the **3D Data Course** repository! This repository aims to provide a comprehensive set of tutorials on 3D Data Processing using Python. Whether you're a beginner or an experienced practitioner, this resource will guide you through the fundamentals and advanced concepts of 3D for Digital Twins. This Open Course initiative is made possible by the financial contribution from the digital twins @ITC -project granted by the ITC faculty of the University of Twente. We are thankful for the support, without which this could not have been possible.

## Table of Contents

1. [Introduction to 3D Data Processing for Digital Twins](#introduction)
2. [Getting Started](#getting-started)
3. [Installation](#installation)
4. [Course Tutorials](#tutorials)
    - [Tutorial 1: 3D LiDAR Workflows](#tutorial-1)
    - [Tutorial 2: ALS LiDAR Classification with Deep Learning](#tutorial-2)
    - [Tutorial 3: 3D Indoor Unsupervised Segmentation (SAM)](#tutorial-3)
    - [Tutorial 4: 3D Point Cloud Detection for Indoor Mapping](#tutorial-4)
    - [Tutorial 5: 3D Data Integration](#tutorial-5)
    - [Tutorial 6: COMING SOON](#tutorial-6)
    - [Tutorial 7: COMING SOON](#tutorial-7)
    - [Tutorial 8: COMING SOON](#tutorial-8)
    - [Tutorial 9: COMING SOON](#tutorial-9)
5. [Examples](#examples)
6. [Contributing](#contributing)
7. [License](#license)

## Introduction <a name="introduction"></a>

3D Data Processing has gained significant traction in various fields, notably geospatial mapping and digital twins. This repository serves as a course and code learning hub for understanding and implementing 3D data processing techniques using Python and Open-Source Tools.

## Getting Started <a name="getting-started"></a>

Before diving into the tutorials, make sure you have the necessary tools and libraries installed. Please refer to the [Installation](#installation) section for detailed instructions.

## Installation <a name="installation"></a>

To get started with 3D Data Processing, you'll need to set up your environment. Each code package is grounded with a how-to guide accessible on this [Medium Page](https://medium.com/@florentpoux). You then have a section dedicated to the local setup.
It usually involves this:

```bash
# Clone the repository
git clone https://github.com/username/3d-deep-learning.git

# Navigate to the project directory
cd 3d-data-processing

# Install miniconda with Python version 3.10

# Create a virtual environment (optional but recommended)
conda create -n DEEPTUTO python=3.10

# Activate the virtual environment
conda activate

# Install dependencies using requirements (if set-up)
pip install -r requirements.txt

#Install dependencies using the given libraries in the Medium Article
pip install numpy matplotlib rasterio laspy open3d
```

## Tutorials <a name="tutorials"></a>

### Tutorial 1: 3D LiDAR Workflows <a name="tutorial-1"></a>

The tutorial covers Python Automation combining 3D Point Clouds, Meshes, and Voxels for advanced analysis.

For starting the tutorial, please refer to the [tutorials](tutorials/) directory, and chose the relevant one

### Tutorial 1: Understanding 3D Data <a name="tutorial-1"></a>

In this tutorial, we'll cover the basics of working with 3D data, including formats, visualization, and common preprocessing techniques.

📖 [3D Python Workflows for LiDAR City Models: A Step-by-Step Guide](https://towardsdatascience.com/3d-python-workflows-for-lidar-point-clouds-100ff40e4ff0?sk=8fcb54d8f81534f0e73a5cd9116a6f9f)

### Tutorial 2: ALS LiDAR Classification with Deep Learning <a name="tutorial-2"></a>

The Ultimate Python Guide to structure large LiDAR point cloud for training a 3D Deep Learning Semantic Segmentation Model with the PointNet Architecture.

📖 [3D Deep Learning Python Tutorial: PointNet Data Preparation](https://towardsdatascience.com/3d-deep-learning-python-tutorial-pointnet-data-preparation-90398f880c9f?sk=b781f4477847b02fab5f17d31108af95)

### Tutorial 3: 3D Indoor Unsupervised Segmentation (SAM) <a name="tutorial-3"></a>

How to build a Semantic Segmentation Application for 3D Point Clouds leveraging SAM and Python. Bonus: Code for Projections and…

Coming soon.

### Tutorial 4: 3D Point Cloud Detection for Indoor Mapping <a name="tutorial-4"></a>

A 10-step Python Guide to Automate 3D Shape Detection, Segmentation, Clustering, and Voxelization for Space Occupancy 3D Modeling of Indoor Point Cloud Datasets.

📖 [3D Point Cloud Shape Detection for Indoor Modelling](https://towardsdatascience.com/3d-point-cloud-shape-detection-for-indoor-modelling-70e36e5f2511?sk=ba5e0b8aec07c44405d4e3bfa6f7900b)

### Tutorial 5: 3D Data Integration <a name="tutorial-5"></a>

Integrate 3D spatial data with Python and explore essential processing steps for reading, loading, transforming, and visualizing 3D point clouds, meshes, cityGML models, voxels, vector data, satellite raster, and 360 images.

Coming soon.

### Tutorial 6: Deploying 3D Models in Applications <a name="tutorial-6"></a>

Coming soon.

### Tutorial 7: Deploying 3D Models in Applications <a name="tutorial-7"></a>

Coming soon.

### Tutorial 8: Deploying 3D Models in Applications <a name="tutorial-8"></a>

Coming soon.

### Tutorial 9: Deploying 3D Models in Applications <a name="tutorial-9"></a>

Coming soon.

## Contributing <a name="contributing"></a>

We welcome contributions! If you have an idea for a new tutorial or want to improve existing content, please refer to the [contributing guidelines](CONTRIBUTING.md).

Main author: 
- Dr. Florent Poux

Course Tutorial Co-Authors:
- Dr. Sander Oude Elberink
- Dr. Mila Koeva
- Dr. Ville Lehtola
- Dr. Pirouz Nourian
- Dr. Paulo Raposo
- Prof G. Vosselman

## License <a name="license"></a>

This open course initiative is made possible by the financial contribution from the digital twins @ITC -project granted by the ITC faculty of the University of Twente. We thank the initiative very much.
This repository is licensed under the [MIT License](LICENSE).

---

Feel free to reach out with any questions, feedback, or suggestions. Happy learning! 🚀
