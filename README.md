<div id="top"></div>

<!-- INTRO -->

# Mini DICOM Viewer
> :warning: **The project is a demo and not a real DICOM Viewer**: Be very careful here!

<br/>

## What is a DICOM Viewer?

DICOM stands for “Digital Imaging and Communications in Medicine”. It is an international standard for medical imaging. 
A DICOM file consists of a header and image data sets packed into a single file. 
The information within the header is organized as a constant and standardized series of tags. 

Inconveniently, in contrast to other image file formats such as JPEG or TIFF, DICOM files are not recognized by Operating System (Windows®, Mac) as image files. 
To view these images on your computer, you will have to use a DICOM viewer, which will interpret the file information and display it as an image.

<br/>

<!-- ABOUT THE PROJECT -->

## About The Project

The application offers two interfaces for viewing persistent data on the database.

* Explorer
  
[![Explorer Studies Screen Shot][explorer-studies]](https://github.com/angelolamonaca/mini_dicom_viewer-react_frontend)
  
[![Explorer Series Screen Shot][explorer-series]](https://github.com/angelolamonaca/mini_dicom_viewer-react_frontend)
  
[![Explorer Files Screen Shot][explorer-files]](https://github.com/angelolamonaca/mini_dicom_viewer-react_frontend)

* Search

[![Search Screen Shot][search]](https://github.com/angelolamonaca/mini_dicom_viewer-react_frontend)


<p align="right">(<a href="#top">back to top</a>)</p>

<!-- GETTING STARTED -->

## Getting Started

### Prerequisites

* Docker
* Docker-compose

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/angelolamonaca/mini_dicom_viewer.git
   ```

2. Run docker compose up command
   ```shell
   docker compose up -d
   ```

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- TECHNOLOGY STACK -->

## Technology stack

- ### Backend

API with GraphQL, Node.js, and Sequelize

- ### Frontend

Frontend with ReactJS and MaterialUI

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- LICENSE -->

## License

Distributed under the Apache License 2.0. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTACT -->

## Contact

Angelo Lamonaca - [@Linkedin Profile](https://www.linkedin.com/in/angelolamonaca/)

Project Link: [https://github.com/users/angelolamonaca/projects/3](https://github.com/users/angelolamonaca/projects/3)

<p align="right">(<a href="#top">back to top</a>)</p>


[explorer-studies]: .github/_media/preview-explorer-studies.png
[explorer-series]: .github/_media/preview-explorer-series.png
[explorer-files]: .github/_media/preview-explorer-files.png
[search]: .github/_media/preview-search.png
