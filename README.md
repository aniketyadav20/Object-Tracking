
[![LinkedIn][linkedin-shield]][linkedin-url]

# Object Detection

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project
      </a>
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
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project
Videos can be treated as stack of pictures called frames. Here I am comparing different frames(pictures) to the first frame which should be static(No movements initially). We create 4 windows that are: - Video itself, - HSV colour, - Bitwise frame. In python we can do it easily as you can see in code.

<p align="center">
<img src="https://pysource.com/wp-content/uploads/2018/01/object-detection-using-hsv-color.jpg"
 alt="Logo" width="500" height="350">
</p>


### Built With

We use opencv to accomplish this task.
you must know about these terms also:
* [HSV](https://en.wikipedia.org/wiki/HSL_and_HSV): HSL (for hue, saturation, lightness) and HSV (for hue, saturation, value; also known as HSB, for hue, saturation, brightness) are alternative representations of the RGB color model, designed in the 1970s by computer graphics researchers to more closely align with the way human vision perceives color-making attributes. In these models, colors of each hue are arranged in a radial slice, around a central axis of neutral colors which ranges from black at the bottom to white at the top.

<p align="center">
<img src="https://www.researchgate.net/profile/Ravindran-G/publication/321126312/figure/fig1/AS:561582682722304@1510903153364/llustration-of-the-HSV-Color-Space-B-Color-Feature-Extraction-Color-feature-is-extracted.png"
 alt="Logo" width="250" height="300">
</p>

* [Arithmetic Operations On Image](https://www.youtube.com/watch?v=Xq5UK_TB8J0): Bitwise operations are used in image manipulation and used for extracting essential parts in the image.


<!-- GETTING STARTED -->
## Getting Started

### Prerequisites
* Any python Compiler (except google colab)

### Installation

1. Install packages
   ```sh
   pip install opencv-python
   ```



<!-- USAGE EXAMPLES -->
## Usage
Object Detection is a computer technology related to computer vision, image processing, and deep learning that deals with detecting instances of objects in images and videos.



<!-- ROADMAP -->
## Roadmap

1. In this AI world, opencv library is must to learn about AI. 
2. The main goal of this repository is object detection. We only require opencv library for this.
3. First a fall, we import opencv library.
4. Start the camera by using live camera using videocapture(0), if you want to perforn on any video then simply change 0 to the address of video in videocapture.
5. Then, make create the window to set the HSV parameters to track the object.
6. Then we read a video frame-wise and convert each frame to HSV.
7. Now, we get the HSV parameters from the Tracking window and set it on the frame.
8. WE perform bitwise operation on the masked image that we get from above.
9. Now, show all the frames on the screen.
10. Frame is changing continuously so when we show output frame, it is like a video.

Here you go! This was a simple way to detect faces, eyes, and happiness 😎.
<p align="center">
<img src="https://i.imgur.com/gWuwZwr.gif"
 alt="Logo" width="400" height="200">
</p>

## Contact

Aniket Yadav - [Medium](https://aniketyadavv.medium.com/) - [Gmail](https://yadavaniket0820gmail.com/)
<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/aniket-yadav-2008/
