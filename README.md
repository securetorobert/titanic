# How to complete a Kaggle Competition with Machine Learning

I used DataCamp's tutorials for this. There are three notebooks which will take you through EDA to predictions.

I use Anaconda to manage my environments. Take a look at environment.yml for setup, and you can use requirements.txt to install requirements into a Python 3.6 environment.

<p align="center">
<img src="img/nytimes.jpg" width="600">
</p>


## Prerequisites

Not a lot. It would help if you knew

* programming fundamentals and the basics of the Python programming language (e.g., variables, for loops);
* a bit about `pandas` and DataFrames;
* a bit about Jupyter Notebooks;
* your way around the terminal/shell.


**However, I have always found that the most important and beneficial prerequisite is a will to learn new things so if you have this quality, you'll definitely get something out of this code-along session.**


 [Anaconda distribution](https://www.anaconda.com/download/) of Python 3 (see below)


## Getting set up computationally

### 1. Clone the repository

To get set up for this live coding session, clone this repository, or get the empty files from datacamp repo. You can do so by executing the following in your terminal:

```
git clone https://github.com/datacamp/datacamp_facebook_live_titanic
```

Alternatively, you can download the zip file of the repository at the top of the main page of the repository. If you prefer not to use git or don't have experience with it, this a good option.

### 2. Download Anaconda (if you haven't already)

If you do not already have the [Anaconda distribution](https://www.anaconda.com/download/) of Python 3, go get it (n.b., you can also do this w/out Anaconda using `pip` to install the required packages, however Anaconda is great for Data Science and I encourage you to use it).

### 3. Create your conda environment for this session

Navigate to the relevant directory `datacamp_facebook_live_titanic` and install required packages in a new conda environment:

```
conda env create -f environment.yml
```

This will create a new environment called fb_live_titanic. To activate the environment on OSX/Linux, execute

```
source activate fb_live_titanic
```
On Windows, execute

```
activate fb_live_titanic
```


### 4. Open your Jupyter notebook

In the terminal, execute `jupyter notebook`.

Then open the notebook `1-titanic_EDA_first_models.ipynb` and we're ready to get coding. Enjoy.


### Code
The code in this repository is released under the [MIT license](LICENSE). Read more at the [Open Source Initiative](https://opensource.org/licenses/MIT). All text remains the Intellectual Property of DataCamp. If you wish to reuse, adapt or remix, get in touch with me at hugo at datacamp com to request permission.
