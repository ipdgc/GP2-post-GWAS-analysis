<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/github_username/repo_name">
    <img src="images/GP2_logo.png" alt="Logo" width="300" height="70">
  </a>

<h3 align="center">Post-GWAS analysis</h3>

  <p align="center">
    One of the projects from the 2021 GP2/IPDGC Hackathon. The related manuscript can be found on bioRxiv: https://www.biorxiv.org/content/10.1101/2022.05.04.490670v1
    <br />
    Contributers: Julie Lake, Raquel Real, Bernabe Bustos, Bharati Jadhav, Lesley Wu
    <br />
  </p>
</div>


<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#quick-description">Quick Description</a></li>
        <li><a href="#background/motivation">Background/motivation</a></li>
        <li><a href="#workflow-summary">Workflow Summary</a></li>
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
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

![Project Screen Shot][project-screenshot]

### Quick Description

The goal for this project was to develop a pipeline for some common post-GWAS follow up analyses.

### Background/motivation

Genome-wide association studies (GWAS) are popular and useful tools for investigating genetic risk associated with a trait. Successful GWAS should be accompanied with various follow-up analyses such as heritability estimates and polygenic risk scores (PRS). It can be confusing and time-consuming when it comes to choosing and coding GWAS follow-up analyses. This workflow serves as an example for how to perform some common GWAS follow-up analyses using [AMP-PD](https://amp-pd.org/) data to help give guidance to other researchers performing GWAS.      

### Workflow Summary

### PD_LRRK2_hackathon.ipynb
1. Setting up
2. Preparing clinical files
3. Genetic QC
4. Heritability
5. Genetic risk score 

### runs_of_homozygosity.ipynb
1. Setting up
2. Quality control
3. Runs of homozygosity

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

### Prerequisites

* [Plink](https://www.cog-genomics.org/plink/)
* [GCTA](https://yanglab.westlake.edu.cn/software/gcta/#Overview)

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/ipdgc/GP2-post-GWAS-analysis.git
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

These notebooks can be directly uploaded to your workspace on Terra. They are designed to be used on Terra with AMP-PD data, but by changing the file paths you can use these notebooks anywhere other than Terra and for any data.

_For more examples, please refer to Plink [documentation](https://www.cog-genomics.org/plink/) and GCTA [documentation](https://yanglab.westlake.edu.cn/software/gcta/#Overview)_

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [AMP-PD](https://amp-pd.org/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[project-screenshot]: images/project_screenshot.png

