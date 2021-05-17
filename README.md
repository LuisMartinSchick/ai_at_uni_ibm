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
git clone https://github.com/mperini/ai_at_uni_ibm.git
```

- Downloading the whole repository as a ZIP file, and then unzip it in the desired location.

### Setup Environment for the Hackaton
For the Hackaton competition you will be part of a team, and you'll have to collaborate together to solve the case. Given the virtual nature of the event (thanks COVID) you'll have to decide with your team what collaboration tools you want to use to work toeghter. 

In the following we provide indications for local development (on your own machine) and for shared live development using [Visual Studio Code](https://code.visualstudio.com/).

#### Local development
Be sure to have Python installed on your machine. We recommend using the [Anaconda](https://docs.anaconda.com/anaconda/install/) distribution. 
In order not to clash with other package dependencies you might already have, the first step is to create a virtual environment. Open an Anaconda terminal and type: 
```
conda create --name aiatuni python=3.7
```
Then navigate to the Ai@University folder you have previously cloned/downloaded via:
```
cd path/to/the/folder/ai-at-uni-ibm
```
We have provided a list of packages in the `requirement.txt` file, that give you a starting point to go through the demo use case, and are definitely enough also for the hackaton. Running the following command will install all the necessary packages:
```
pip install -r requirements.txt
```

Once everything is installed, you can activate your environment via:
```
conda activate aiatuni
```

To open the jupyter notebook menu, navigate in the terminal to the folder containing the Ai@University material (using the `cd` command). Then type:
```
jupyter notebook
```
and you should be redirected via your browser to the Home view. From there, click on the notebook you wish to open, and voilà.

#### Using VS Code
Follow [these instructions](https://docs.microsoft.com/en-us/visualstudio/liveshare/) to download Visual Studio Code and the Live Share extension. 

From the Extension Marketplace (within VS Code) also download the Python extension by searching for `@id:ms-python.python`. Once that is installed re-start the program, and open the Ai@University folder from within the project. On the bottom left part of the screen, in the blue bar, click where it says "Python 3.8.6 64-bit" (or something similar depending on the Python version installed on your machine) and select the `(aiatuni: conda)`.

At this point you can open the desired notebook (or create a new one). Before you see the interactive view you might be prompted to trust the notebook content. Click on Trus (if you trust us!) and you are ready to code.

To enable the live share now click on "Live Share" on the bottom blue bar. You'll be asked to authenticate using your GitHub or Microsoft account. Follow the instructions provided to connect your account to Visual Studio Code. If everything went well you are now able to invite other team members to join your session, or join theirs.


__Author:__ Marco Perini, Data Scientist at IBM (marco.perini@ibm.com) 

Copyright © IBM Corp. 2021. This repository and its contents are released under the terms of the MIT License.