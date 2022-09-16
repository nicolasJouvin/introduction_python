# Github Repository accompanying Evry's M2 course on Machine Learning with Python

Course taught between September and October 2022 at Evry university's M2 *data science*
* Author : [Nicolas Jouvin](https://nicolasjouvin.github.io)


> First session : tuesday 20th september, 14h-17h15 (salle info)

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