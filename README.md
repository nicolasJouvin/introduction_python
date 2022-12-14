# Github Repository accompanying Evry's M2 course on Machine Learning with Python

Course taught between September and October 2022 at Evry university's M2 *data science*
* Author : [Nicolas Jouvin](https://nicolasjouvin.github.io)


### Dates & exam

> Exam : tuesday 8th November, **15h15-17h** (1h45, salle 113) : le sujet sera en anglais et en français.

  * Examen sur papier : pas le droit à la machine 
  * Aucun documents annexe autorisé
  * Programme : tous les cours et TP (Syntaxe, objets "basiques", modules NumPy, Pandas & matplotlib)
  
  

### Past
> **Session 4** : wednesday 19th october, 14h30-17h30 (salle info)


**TODO** You'll need to

	*  Finish the NumPy exercise sheet & look at the correction
	* Read the Pandas tutorial, choose the one you prefer
		* https://pandas.pydata.org/pandas-docs/stable/user_guide/10min.html
		* https://www.w3schools.com/python/pandas/default.asp (focus on the "basic" part)
	* Look at the Pandas warmup notebook of Tamas Gal : https://github.com/escape2020/school2022/blob/main/pandas/1_pd_warmup.ipynb
	* We'll do the following exercise sheet (credits to Fabrice Rossi) : https://apiacoa.org/publications/teaching/python/intro-pandas-students.pdf
	* It requires to download the file [bank-short.csv](https://apiacoa.org/publications/teaching/datasets/bank-short.csv) and [departments.csv](https://apiacoa.org/publications/teaching/datasets/departements.csv)
	* Correction TP Pandas [sur le site de Fabrice Rossi](https://apiacoa.org/publications/teaching/python/intro-pandas.pdf) 

> Session 3 : tuesday 4th october, 14-17h15 (salle info)

**TODO**

	* Read the Numpy tutorial : https://courspython.com/bases-numpy.html#
	* Read the Matplotlib tutorial : https://courspython.com/introduction-courbes.html
	* Look at the numpy warmup notebook in the `/Numpy/` folder
	* Begin the NumPy exercise sheet int the `/Numpy/` folder





# Cloning the repository

Go to your desired folder on your laptop and open a terminal (or git bash for windows users), then type 

```
git clone git@github.com:nicolasJouvin/introduction_python.git
```


# What you need to do before the first course

> **Note** For this course, you will use your own individual laptop (whatever the OS). If you don't have one, you can pair with some colleagues. 


Here is the list of what should be installed before the 1st session, for those who have a machine:

### Mandatory

 * The  [anaconda](https://www.anaconda.com/products/distribution) distribution : this is Python + lots of useful scientific package.
 * A [conda environment](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html) named  `M2Evry` with Python >= 3.8
     * For linux/MacOS: open a terminal and type `conda create --name M2Evry python=3.10` 
     * For windows : open the *conda prompt* and type `conda create --name M2Evry python=3.10`
 * run `conda activate M2Evry`: this activates the Python environment you just created
 * run `pip install notebook` to install [jupyter notebook](https://www.dataquest.io/blog/jupyter-notebook-tutorial/). This will allow you to open `introduction_python_intro.ipynb` in you default browser.
 * run `pip install -r requirements.txt`

### Strongly recommanded
 
 * [Git](https://git-scm.com/book/fr/v2/D%C3%A9marrage-rapide-Installation-de-Git) : you can type `git clone git@github.com:nicolasJouvin/introduction_python.git` to track the course's github repository.
 * A Python development environment (IDE), I recommend [Visual Studio Code](https://code.visualstudio.com/docs/languages/python) and its python add-ins. You can also install one of the two following but I will provide a very limited help for those:
     * [Pycharm Community](https://www.jetbrains.com/fr-fr/pycharm/download/) 
     * **Spyder** : comes with anaconda
     
### Optional 

You can look at Python tutorials online and/or play with the introductory notebook: `./intro/Basics_of_Python.ipynb`.
