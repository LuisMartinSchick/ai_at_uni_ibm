# AI@University
This repository provides the necessary material to participate in the AI@University workshop. 

### Folder Structure
    .
    ├── data              # Data folder containing the data for the demo use case
    ├── results           # Folder containing saved models and other artifacts for the demo use case
    ├── hackaton          # Folder containing data and guidelines for hackaton competition
    ├── AIatUniversity_preparation_material.ipynb      # Jupyter Notebook with the Demo Use Case 
    └── README.md
    
### How to use this repository
This is not meant to be a project repository, where all the files are used to compile some application from source code. It is instead a reference point for participants to easily access the data and some of the material used during the workshop.

You can access the material by:

- Cloning this repository on your local machine via:
```
git clone https://github.com/mperini/at_at_uni_ibm.git
```

- Downloading the whole repository as a ZIP file

### Setup Environment for the Hackaton
For the Hackaton competition you will be part of a team, and you'll have to collaborate together to solve the case. Given the virtual nature of the event (thanks COVID) you'll have to decide with your team what collaboration tools you want to use to work toeghter. 

In the following we provide indications for local development (on your own machine) and for shared development using [Google Colab](https://colab.research.google.com/notebooks/intro.ipynb).

#### Local development
Be sure to have Python installed on your machine. We recommend using the [Anaconda](https://docs.anaconda.com/anaconda/install/) distribution. 
In order not to clash with other package dependencies you might already have, the first step is to create a virtual environment. Open an Anaconda terminal and type: 
```
conda create --name aiatuni --file requirements.txt
```
We have provided a list of packages in the `requirement.txt` file, that give you a starting point to go through the demo use case, and are definitely enough also for the hackaton. Running the command above will also install all the packages. 

Once everything is installed, you can activate your environment via:
```
conda activate aiatuni
```

To open the jupyter notebook menu, navigate in the terminal to the folder containing the Ai@University material (using the `cd` command). Then type:
```
juypter notebook
```
and you should be redirected via your browser to the Home view. From there, click on the notebook you wish to open, and voilà.

#### Using Colab
WIP


__Author:__ Marco Perini, Data Scientist at IBM (marco.perini@ibm.com) 

Copyright © IBM Corp. 2021. This repository and its contents are released under the terms of the MIT License.