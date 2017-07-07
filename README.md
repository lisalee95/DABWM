# GovTechDay3
Data, Workbooks and Slides for GovTechDay3

## Installation

1.  Clone this repository using Git. Git has already been installed on your student notebook. Launch `Git Bash` and run the following command:

        git clone git@github.com:realanalyticsio/GovTechDay3.git

    or download as a [zip file](https://github.com/realanalyticsio/GovTechDay3/archive/master.zip) and unzip it. Change to this directory.

2. Anaconda has already been installed in your student notebook. Alternatively, you can also install [Anaconda](https://www.continuum.io/downloads) (large) or [Miniconda](https://conda.io/miniconda.html) (small) yourself. Launch `Anaconda Prompt` and run the following command to see all available conda environments:

        conda info --envs

3. A `govtech` conda environment has already been created on your student notebook but you will need to update its dependencies and activate it:

        conda env update -f environment.yml
        source activate govtech  # Linux or OS/X
        activate govtech         # Windows

4. If the `govtech` conda environment is missing, run the following commands to create it and activate the environment:

        conda env create -f environment.yml
        source activate govtech  # Linux or OS/X
        activate govtech         # Windows

5. Test your installation:

        python -c 'import pandas, numpy, seaborn, matplotlib.pyplot, requests, sklearn'

6. Finally launch a Jupyter Notebook to start your lab sessions:

        jupyter-notebook

