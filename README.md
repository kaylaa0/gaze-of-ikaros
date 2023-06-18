<a name="readme-top"></a>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/kaylaa0/gaze-of-ikaros">
    <img src="images/logo.png" alt="Logo" width="100" height="100"><br />
    <img src="images/logo_text.png" alt="Logo" height="80">
  </a>

  <p align="center">
    <h3 align="center">Multiclass Semantic Segmentation on Satellite Imagery</h3>
    <br />
    <a href="https://github.com/kaylaa0/gaze-of-ikaros"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/kaylaa0/gaze-of-ikaros">View Demo</a>
    ·
    <a href="https://github.com/kaylaa0/gaze-of-ikaros/issues">Report Bug</a>
    ·
    <a href="https://github.com/kaylaa0/gaze-of-ikaros/issues">Request Feature</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project

Gaze of Ikaros is a computer vision project aimed at enhancing emergency response efforts by utilising the xBD dataset, which contains satellite imagery data of disaster-affected areas, to develop accurate and efficient damage assessment models.

Here's why:
* Automated detection of damaged buildings can also automate dispacting of emergency response units
* Estimating the total distruction of the disaster can help quantifying units to be send to area
* Further work can be used to predict outcomes of disasters

The whole project aims to utilize various tools and research the best solution. In this repository you will find the selected DeepLabV3+ solution from my work which has `0.97` accuracy.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

* [![Tensorflow][Tensorflow.org]][Tensorflow-url]
* [![Keras][Keras.io]][Keras-url]
* [![OpenCV][Opencv.org]][Opencv-url]
* [![SciPy][Scipy.org]][Scipy-url]
* [![NumPy][Numpy.org]][Numpy-url]
* [![Pandas][Pandas.org]][Pandas-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

### Prerequisites

You need to sign up for [xView2](https://xview2.org/) in order to get download links. Once registered, you can retrieve the download links and insert them into the designated link field within the notebook. 
  ```sh
  link = 'Insert download link'
  ```

### Installation

_Google Colab has necessary libraries however if you want to use locally you need to install these libraries_

1. [Get your version of Tensorflow](https://www.tensorflow.org/install)
    ```sh
    pip install tensorflow
    ```
2. Install other libraries
   ```sh
    pip install numpy pandas imageio scipy matplotlib pillow
    ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->
## Usage

You can use provided notebook file in colab.

[![Open In Colab][open-in-colab-shield]][open-in-colab-url]

_You need to setup [Jupyter](https://jupyter.org/) to run locally_

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ROADMAP -->
## Roadmap
- [x] Create README.md
- [ ] Multi-language Support
    - [ ] Japanese

See the [open issues](https://github.com/kaylaa0/gaze-of-ikaros/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE 
## License
See `LICENSE.txt` for more information.
<p align="right">(<a href="#readme-top">back to top</a>)</p>-->

<!-- CONTACT -->
## Contact

Kayla Akyüz - kaylakyuz@gmail.com

Project Link: [GitHub](https://github.com/kaylaa0/gaze-of-ikaros)

[![LinkedIn][linkedin-shield]][linkedin-url] 

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [Multiclass semantic segmentation using DeepLabV3+](https://keras.io/examples/vision/deeplabv3_plus/)
* [xView2](https://xview2.org/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/-kayla-/
[product-screenshot]: images/screenshot.png
[Tensorflow.org]: https://img.shields.io/badge/Tensorflow-FFA800?style=for-the-badge&logo=tensorflow&logoColor=white
[Tensorflow-url]: https://www.tensorflow.org/
[Keras.io]: https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white
[Keras-url]: https://keras.io/
[Scipy.org]: https://img.shields.io/badge/SciPy-0054A6?style=for-the-badge&logo=scipy&logoColor=white
[Scipy-url]: https://scipy.org/
[Numpy.org]: https://img.shields.io/badge/NumPy-4DABCF?style=for-the-badge&logo=numpy&logoColor=white
[Numpy-url]: https://numpy.org/
[Pandas.org]: https://img.shields.io/badge/Pandas-130654?style=for-the-badge&logo=numpy&logoColor=white
[Pandas-url]: https://pandas.pydata.org/
[Opencv.org]: https://img.shields.io/badge/OpenCV-8ADA67?style=for-the-badge&logo=opencv&logoColor=white
[Opencv-url]: https://opencv.org/
[open-in-colab-shield]: https://colab.research.google.com/assets/colab-badge.svg
[open-in-colab-url]: https://colab.research.google.com/github/kaylaa0/gaze-of-ikaros/blob/main/DeepLabV3.ipynb