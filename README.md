



<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/MHH-RCUG/scrnaseq_app">
    <img src="www/MHH.png" alt="Logo">
  </a>

  <h3 align="center">scrnaseq_app</h3>

  <p align="center">
    A shiny app to generate and download plots
    <br />
    <a href="https://github.com/MHH-RCUG/scrnaseq_app"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/MHH-RCUG/scrnaseq_app">View Demo</a>
    ·
    <a href="https://github.com/MHH-RCUG/scrnaseq_app/issues">Report Bug</a>
    ·
    <a href="https://github.com/MHH-RCUG/scrnaseq_app/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Upload .rds file](#upload-rds-file)
  * [Select genes](#select-genes)
    * [Select genes through UI](select-genes-through-ui)
    * [Select genes through an excel file with header (EnsemblIDs)](select-genes-through-an-excel-file-with-header)
    * [Select genes through an excel file without header (EnsemblIDs)](select-genes-through-an-excel-file-without-header)
* [Usage](#usage)
* [Roadmap](#roadmap)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)
* [Acknowledgements](#acknowledgements)



<!-- ABOUT THE PROJECT -->
## About The Project

![screenshot](https://github.com/MHH-RCUG/scrnaseq_app/blob/master/www/screenshot.PNG)

### Built With

* [R](https://www.r-project.org/)
* [Shiny from RStudio](https://shiny.rstudio.com/)
* [Seurat](https://satijalab.org/seurat/)



<!-- GETTING STARTED -->
## Getting Started

To get the app running you need to follow these simple steps.

### Upload .rds file
First you need to upload a .rds file containing your Seurat object. If you don't have this file, you can use this [example](https://owncloud.gwdg.de/index.php/s/rRawkhIOVe1T5qi).

### Select genes

#### Select genes through UI
Once the .rds file is uploaded and processed, you can click on the field below "Genes" and select your genes by clicking or searching. To delete genes you have to click on the gene and hit the backspace key.

#### Select genes through an excel file with header (EnsemblIDs)
You can select genes by uploading an .xlsx file ([example](https://owncloud.gwdg.de/index.php/s/ZwY0iVPji6uBVKO)).  
The spreadsheet has to look something like this:

| EnemblIDs | Genes       |
|-----------|-------------|
| First ID  | First Gene  |
| Second ID | Second Gene |

The app will only read the first column where it expects EnsemblIDs, whereas rhe column "Genes" is optional.

#### Select genes through an excel file without header (EnsemblIDs)
If your .xlsx file contains no header please uncheck the checkbox. Otherwise the first row/ EnsemblID will not show up in the selection.

### Installation

1. Clone the repo
```sh
git clone https://github.com/github_username/repo_name.git
```
2. Install NPM packages
```sh
npm install
```



<!-- USAGE EXAMPLES -->
## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_



<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/github_username/repo_name/issues) for a list of proposed features (and known issues).



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE 
## License

Distributed under the MIT License. See `LICENSE` for more information.
-->


<!-- CONTACT -->
## Contact

Your Name - [@twitter_handle](https://twitter.com/twitter_handle) - email

Project Link: [https://github.com/github_username/repo_name](https://github.com/github_username/repo_name)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

* [scrnaseq](https://github.com/ktrns/scrnaseq)
* [README-Template](https://github.com/othneildrew/Best-README-Template)
* []()

[![Contributors](https://img.shields.io/github/contributors/MHH-RCUG/scrnaseq_app)](https://github.com/MHH-RCUG/scrnaseq_app/graphs/contributors)
[![GitHub issues](https://img.shields.io/github/issues/MHH-RCUG/scrnaseq_app)](https://github.com/MHH-RCUG/scrnaseq_app/issues)
[![GitHub forks](https://img.shields.io/github/forks/MHH-RCUG/scrnaseq_app)](https://github.com/MHH-RCUG/scrnaseq_app/network)
[![GitHub stars](https://img.shields.io/github/stars/MHH-RCUG/scrnaseq_app)](https://github.com/MHH-RCUG/scrnaseq_app/stargazers)

# scrnaseq_app
Shiny app for visualisation of scRNASeq data

Link to singularity container: [Link](http://172.24.148.210:3838/)

File for testing purposes: [Link](https://owncloud.gwdg.de/index.php/s/rRawkhIOVe1T5qi)
