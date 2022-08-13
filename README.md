

<h3 align="center">Dog Specie Detector</h3>

  <p align="center">
    A simple program that detects various dog species using AI and Neural Networks
    <br />
    <a href="https://github.com/ultralytics/yolov5"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/github_username/repo_name">View Demo</a>
    ·
    <a href="https://github.com/github_username/repo_name/issues">Report Bug</a>
    ·
    <a href="https://github.com/github_username/repo_name/issues">Request Feature</a>
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
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project


This is a simple AI program that detects the type of dog species thrown at it, which includes 120 dog species and thousands of images as training sets.




### Built With

 [![Python][Python.com]][Python-url]




<!-- GETTING STARTED -->
## Getting Started

The following instructions will help you install the program and get it running locally
### Prerequisites

A lits of things to consider before using the program

* Cloning the Yolov5 repository
  ```python
  git clone https://github.com/ultralytics/yolov5
  ```
* Beware of changing file names and model names as it can mess with the program as the pre-trained model is already up on the repository, Ex: dog.yaml...

### How to use
1. Clone the repo
   ```python
   git clone https://github.com/Moad-S/Dog-Specie-Detector.git
 
2. Example of how the file structure should look like.

   ![image](https://user-images.githubusercontent.com/75837889/184492699-f1ad9b09-46fb-4f3d-ba42-89269fb5f4ff.png)





<!-- USAGE EXAMPLES -->
## Usage

This project can be used as a guide on how neural networks work in conjuction with image detection. 

1. We firstly train the model using randomised weights
   ```python
   %cd yolov5
   !python train.py --img 640 --batch 32 --epochs 30 --data dog.yaml --weights '' --cfg yolov5s.yaml 
   
2. We continue training the pre-trained model for better results

3. We then use the detection command after the training is complete 

   ```python
   !python /content/yolov5/detect.py --weights /content/best.pt --img 640 --conf 0.15 --source /content/doggus/Untitled4.jpg

   

![alt text](https://cdn.discordapp.com/attachments/901469400689954866/1005600199684665374/unknown.png)


![alt text](https://media.discordapp.net/attachments/901469400689954866/1005600199353323530/unknown.png?width=358&height=675)




<!-- ROADMAP -->
## Roadmap

- [x] Finishing the code
- [x] Training
- [x] Comparison
    - [x] Get higher accuracy 





<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!







<!-- CONTACT -->
## Contact

Name - Moad Sati - saatimoad@yahoo.fr

Project Link: ["link"](https://github.com/Moad-S/Dog-Specie-Detector.git)





<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/github_username/repo_name.svg?style=for-the-badge
[contributors-url]: https://github.com/github_username/repo_name/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/github_username/repo_name.svg?style=for-the-badge
[forks-url]: https://github.com/github_username/repo_name/network/members
[stars-shield]: https://img.shields.io/github/stars/github_username/repo_name.svg?style=for-the-badge
[stars-url]: https://github.com/github_username/repo_name/stargazers
[issues-shield]: https://img.shields.io/github/issues/github_username/repo_name.svg?style=for-the-badge
[issues-url]: https://github.com/github_username/repo_name/issues
[license-shield]: https://img.shields.io/github/license/github_username/repo_name.svg?style=for-the-badge
[license-url]: https://github.com/github_username/repo_name/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/linkedin_username
[product-screenshot]: images/screenshot.png
[Python.com]: https://www.python.org/static/community_logos/python-logo.png
[Python-url]: https://www.python.org/psf-landing/
