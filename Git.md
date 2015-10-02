#Git
In this section, we present a brief history of git an an overview of version control. 

## A Brief History of Git 
Git originated from the Linux kernel, a very large open source project. For most of the life of its maintainence, changes to the kernel were passed as patches and archived files. At the end of the maintence (2002), the project began using a proprietary DVCS called BitKeeper. 

In 2005, Bitkeeper's free-of-charge status was revoked. This drove the Linux development community (and the Linux creator, Linus Torvalds) to develop a separate tool based on things they learned using BitKeeper. 

Goals of the New System: 
* Speed
* Simple design
* Strong support for non-linear development (thousands of parallel branches)
* Fully distributed
* Able to handle large projects like the Linux kernel efficiently (speed and data size)

With these goals in mind, Git was created in 2005. 

**Source:** https://git-scm.com/book/en/v2/Getting-Started-A-Short-History-of-Git

####To Install
1. Please go to the following link: https://git-scm.com/
2. Go to the download page and download git for your appropriate operating system.

## Version Control 

To understand Git, one must have a basic understanding of version control. The Git website describes version control as the following 
> Version control is a system that records changes to a file or set of files over time so that you can recall specific versions later. 

###Example
Suppose you create a file called `HelloWorld.py` with some initial content, as shown below. 

```
print("Hello World!")
```

This is then checked in as *Version 0*. 

You then decide you'd like to add more code to the file so you make the following change. 

```
print("This is an example program that shows how to print lines to the console.")
print("Hello World!")
```

After checking in these changes, also refered to as a *commit*, this updated version of the code would be version 1. You can also change multiple files at once and check all of them in at the same time. 

The image below shows a visual example of the process described above: 
![Commit!](https://github.com/peemin/CSCI-5828-Git-and-Github/blob/mw-branch/Commits.jpg "Image depicting a version control example")

Version Control is very useful for the following reasons: 
* If for some reason, you need to go back to an older version of your file or files, **you can revert the project back to a previous state**
* **You can compare changes over time.**  This is useful for the following reasons: 
 * Without version control, every time a change is made, a new file would have to be created. This can result in a cluttered project folder and hard drive. 
 * If a change is made by more than one person and/or on the same date, a labeling system to distinguish between the changes can become very complicated. 
 * If the hard drive fails, if the project is stored locally, the entire history of the project disappears, if it is not simultaneously backed up in other places. 
 * If a coworker needs to look at the changes made between two or more files, all of the files would have to be sent to them for comparison. 

In conclusion, version control provides an easy way to save space, view changes over time, safely store a software project, and compare changes between files. 

**Sources:**https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control
http://www.cs.colorado.edu/~kena/classes/5828/f15/lectures/02-git.pdf

http://blogs.atlassian.com/2012/02/version-control-diffs-patches/

##Next Section

Now that we understand a bit about Version Control, in the next section, we will discuss branching and merging. 
You may also go back to the Table of Contents. 

Next up, head to the material on [GitHub](https://github.com/kenbod/markdown_github_01/blob/master/GitHub.md) 

The following link gives a different, but good explanation of topics explained above: 
http://betterexplained.com/articles/a-visual-guide-to-version-control/
