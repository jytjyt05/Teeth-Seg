# Overview
<div id="top"></div>
Identify teeth in X-ray images using instance segmentation and colored labelling.
This project was originally created by 3 CS students from Boston College: Yuting Ji, Robert Smithers, and Danilla Zunic. It originally used a **PyTorch** based **Unet** for the model but had accuracy less than **80%**. The reason could be the jump between upsampling layers and downsampling layers. As the main developer, to improve the project's performance, I modified the project by using a **Res-Unet** model instead and achieved **90%** accuracy with a Dice Score of 91.


<!-- ABOUT THE PROJECT -->
<p align="center">
  <img src="images/input.png">
</p>
<p align="center">
  <img src="images/predicted.png">
</p>

<p align="right">(<a href="#top">back to top</a>)</p>


### Built With

* [Python](https://www.python.org/)
* [PyTorch](https://pytorch.org/)

<br/>Packages below are recommended to install.

* PyTorch
  ```sh
  pip install torch
  ```
<p align="right">(<a href="#top">back to top</a>)</p>

<!-- Description -->
## Description

Teeth Labelling is not a brand new field of study, though the amount of available data is highly limited. Teeth data is rarely open source, a product of scarcity in related machine learning research as well as protection of patients' privacy.

With this teeth segmentation utility, artifical intelligence can autonomously label teeth scans and identify malformed, missing, or otherwise important concerns relating to the count and placement of teeth. The ability to label teeth in fractions of a second serves as a vital aide to dentistry personnel.

The written paper in CVPR format can be found at 'Teeth seg and label.pdf'; and the Powerpoint can be found at 'Teeth seg and label PPT.pptx'. I hope these will help advance research within the academic community!

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- Content -->
## Content
Due to privacy policy, I cannot provide the data for this model. However, the code is provided above in 'train.ipynb' and 'test.ipynb'. You may copy/reproduce a similar approach for your own x-ray teeth datasets.
```diff
- To read the Paper, please click on the PDF file: 'Teeth seg and label.pdf'
- To see the Powerpoint, please click on the PPTX file: 'Teeth seg and label PPT.pptx'
```

<!-- LICENSE -->
## License
Distributed under the MIT License. See `LICENSE.txt` for more information.
<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
## Contact
Yuting Ji - jiyz@bc.edu

Original Project Link: [https://github.com/RobertSmithers/TeethSegmentation](https://github.com/RobertSmithers/TeethSegmentation)
<p align="right">(<a href="#top">back to top</a>)</p>


<!-- ACKNOWLEDGMENTS -->
## Special Thank to Professor.Wei
* [Biomedical Image Analysis Course](https://bc-cv.github.io/csci3397/s22/)
<p align="right">(<a href="#top">back to top</a>)</p>
