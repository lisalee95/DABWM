# Data Analytics Begins With Me (DABWM)
Data, Workbooks and Slides for DABWM

## Installation

1.  Clone this repository using Git. Git has already been installed on your student notebook. Launch `Git Bash` and run the following command:

        git clone https://github.com/realanalyticsio/DABWM.git

    or download as a [zip file](https://github.com/realanalyticsio/DABWM/archive/master.zip) and unzip it. 
    
2. Change to the DABWM directory that you have cloned or unzip the zip file in Step 1.

3. Anaconda has already been installed in your student notebook. Alternatively, you can also install [Anaconda](https://www.continuum.io/downloads) (large) or [Miniconda](https://conda.io/miniconda.html) (small) yourself. Launch `Anaconda Prompt` and run the following command to see all available conda environments:

        conda info --envs

4. A `dabwm` conda environment has already been created on your student notebook but you will need to update its dependencies and activate it:

        conda env update -f environment.yml
        activate dabwm         # Windows

5. Test your installation:

        python -c "import pandas, numpy, seaborn, matplotlib.pyplot, requests, sklearn"

6. Finally launch a Jupyter Notebook to start your lab sessions:

        jupyter-notebook

