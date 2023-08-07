<div align="center">
<img src="logos/unidata_logo_horizontal.png" width=50% alt="Unidata logo">

# ![](logos/metpy-32x32.png "MetPy logo") I-GUIDE session on Python with Unidata data

</div>


## :keyboard: Getting set up
For this workshop, we have two separate ways you can participate, work ahead, and follow along.
You can follow along using the data and computational resources of the I-GUIDE Platform.
If you prefer or require doing the work on your own computer, you are welcome to do so as well!

### :cloud: Using [I-GUIDE Platform](https://iguide.illinois.edu/platform/discovery/)
You can do all of this work the I-GUIDE Platform for code and data.
This simply requires a web browser and a stable internet connection.
Get to coding!

When you first sign in, it may take a few seconds for your personal workspace to populate and your coding environment to be fully set up.
From here you will discover a Jupyter Lab interface.
You may need to obtain a copy of these materials by hand.
The easiest way is to launch a new terminal within Jupyter Lab and execute the following:
> `git clone https://github.com/dcamron/metpy-iguide`

Then you can interact with the notebooks!
You will be able to download materials and notebooks from your workspace to your computer.

### :computer: Using your computer
**Note that we are not able to plan for any hardware limitations your personal computer might have, and we will not have time during the workshop to diagnose issues on personal computers.**
Please plan to use the I-GUIDE Platform if this is a concern for you.
We will be using and supporting [Conda](https://docs.conda.io/en/latest/) for installing and managing a Python environment from your computer's command line.
Please have this environment prepared ahead of time if you'll be using your own computer.

> 1. [Install Miniconda](https://docs.conda.io/en/latest/miniconda.html#installing) if you don't already have command-line access to `conda`.
> 1. Get a copy of this code!
> You have a few options from the green button above,  
> a. `git clone https://github.com/dcamron/metpy-iguide.git` from your command line, within some directory on your computer.
> [Install git](https://github.com/git-guides/install-git) if necessary.
> If you're comfortable with `git`, we recommend this approach as it will let you keep this code regularly up to date.  
> b. [`Open with GitHub Desktop`](https://desktop.github.com/) if you have and prefer this graphically-focused software.  
> c. [`Download ZIP`]((https://github.com/dcamron/metpy-iguide/archive/refs/heads/main.zip)) if you prefer to get a single snapshot of the code right here and now.
> 1. Wherever you have this code saved, set up your Python environment with `conda env create -f environment.yml` from your command line.  
> 1. Give this some time.
> Once it's done, activate this new environment with `conda activate iguide`.
> Always do this before starting on work for this workshop!
> 1. Launch Jupyter and get to coding with `jupyter lab`.
> Don't forget to activate your environment first!
