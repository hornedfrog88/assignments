<<<<<<< HEAD
# project-performance

Welcome to ProjectTemplate!

This file introduces you to ProjectTemplate, but you should eventually replace
the contents of this file with an introduction to your project. People who
work with your data in the future will thank you for it, including your future
self.

ProjectTemplate is an R package that helps you organize your statistical
analysis projects. Since you're reading this file, we'll assume that you've
already called `create.project()` to set up this project and all of its
contents.

To load your new project, you'll first need to `setwd()` into the directory
where this README file is located. Then you need to run the following two
lines of R code:

	library('ProjectTemplate')
	load.project()

After you enter the second line of code, you'll see a series of automated
messages as ProjectTemplate goes about doing its work. This work involves:
* Reading in the global configuration file contained in `config`.
* Loading any R packages you listed in he configuration file.
* Reading in any datasets stored in `data` or `cache`.
* Preprocessing your data using the files in the `munge` directory.

Once that's done, you can execute any code you'd like. For every analysis
you create, we'd recommend putting a separate file in the `src` directory.
If the files start with the two lines mentioned above:

	library('ProjectTemplate')
	load.project()

You'll have access to all of your data, already fully preprocessed, and
all of the libraries you want to use.

For more details about ProjectTemplate, see http://projecttemplate.net
=======
<<<<<<< HEAD

# assignments

This is the repository for CSX415 assignments. 

The classes uses **git** and **github** for all assignments.  IN order to minimize merge conflicts, always 

- **pull** new assignments from the original "upstream" repository: https://github.com/csx415/assignments 
- **push** to your completed work to your fork of the repository: https://github.com/**{{YOURID}}**/csx415-assignments. 


## Assignment 0: Using git/github

This first assignments sets up your environment to do the assignments related 
to this class. If	you have previously, cloned this repository you may wish to erase it and follow these instructions instead. 
	
	
### In github

In **github**, you need to create your own fork of the repository. Your work 
for this class goes in that fork. **pull request** while a common aspect of 
git based workflows are not used in this class. Code and merges only go one 
way. You will be graded upon what is turned in in your fork of this repository.

- **fork** the project csx415/assignments . with 
- **rename** your project "csx415-assignments"  (This differentiate it from any other repos called assignments and allow me to find your work)
- (Optional) Update your github profile
	
You are done working on github for this repository, perhaps for the last time 
in this class. **git** is your tool, **github** is just a convenient place for
storage. You could just as easily store your repositories on a local harddrive,
shared directory, or some web resource.
	
	
### On your laptop

- **clone** your project from your fork to your workspace (laptop). This downloads the assignments to your laptop.
- **add** a new remote named "upstream" that points to the *class repository*, https://github.com/csx415/assignments  (not your fork of the class repository). 

	
Now test it:

- **pull** from upstream *test-git* branch 
- **merge**  
- **push** to origin *master branch*

(Rhetorical) What changes did that make to your repository?

**Remember:** always **knit** the document as a **PDF** to submit your assignment.   
=======

# assignments

This is the repository for CSX415 assignments. 

The classes uses **git** and **github** for all assignments.  IN order to minimize merge conflicts, always 

- **pull** new assignments from the original "upstream" repository: https://github.com/csx415/assignments 
- **push** to your completed work to your fork of the repository: https://github.com/**{{YOURID}}**/csx415-assignments. 


## Assignment 0: Using git/github

This first assignments sets up your environment to do the assignments related 
to this class. If	you have previously, cloned this repository you may wish to erase it and follow these instructions instead. 
	
	
### In github

In **github**, you need to create your own fork of the repository. Your work 
for this class goes in that fork. **pull request** while a common aspect of 
git based workflows are not used in this class. Code and merges only go one 
way. You will be graded upon what is turned in in your fork of this repository.

- **fork** the project csx415/assignments . with 
- **rename** your project "csx415-assignments"  (This differentiate it from any other repos called assignments and allow me to find your work)
- (Optional) Update your github profile
	
You are done working on github for this repository, perhaps for the last time 
in this class. **git** is your tool, **github** is just a convenient place for
storage. You could just as easily store your repositories on a local harddrive,
shared directory, or some web resource.
	
	
### On your laptop

- **clone** your project from your fork to your workspace (laptop). This downloads the assignments to your laptop.
- **add** a new remote named "upstream" that points to the *class repository*, https://github.com/csx415/assignments  (not your fork of the class repository). 

	
Now test it:

- **pull** from upstream *test-git* branch 
- **merge**  
- **push** to origin *master branch*

(Rhetorical) What changes did that make to your repository?

**Remember:** always **knit** the document as a **PDF** to submit your assignment.   
>>>>>>> 661a2db5cd03c3adb1087e22bdc1af4912d8694c
>>>>>>> 140f6feb4c60821ff44344e012afb3caeb92e88e
