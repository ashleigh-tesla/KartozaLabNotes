# Kartoza Lab Notes

## Notes I learn from Kartoza (Pty) Ltd 

### Week 1

1. Joined _Introduction to the Kartoza Internship Session_
2. Installed all Suggested Essential Software
3. Introduction to *QGIS* Course
4. Start the **Simple Africa Map** project

 > Follow the ![QGIS Road to Nerdvana Episode 15: Making a Small Scale Map of Africa](https://www.youtube.com/watch?v=LJIiZfA7Iio "Making a Small Map of Africa Youtube Video")

5. Attend the Week's Intern Hangout Meeting to get some notes, advice, and corrections required to amend and improve the Final Map


### Week 2

- Polished and then submitted the final **Simple Africa Map**

![Simple Scale Africa Map!](/pics/Simple%20Africa%20Map.png "Simple Africa Map")

- Continuing with the *QGIS* Coursework
- Signing up with ***Open Street Map Organization*** and joining the community helps start contributing to the OSM by digitizing some map features 
- Edited the OSM by:
> 1. adding missing features

 >> ![Open Street Map Area Edit!](/pics/Open%20Street%20Map%20Area%20Edit.jpeg  "Open Street Map Area Edit")

 >> ![Open Street Map Line Edit!](/pics/Open%20Street%20Map%20Line%20Edit.jpeg "Open Street Map Line Edit")

 >> ![Open Street Map Point Edit!](/pics/Open%20Street%20Map%20Point%20Edit.jpeg "Open Street Map Point Edit")

> 2. commenting present features 

![Open Street Map Commenting!](/pics/Open%20Street%20Map%20Comment%20Edit.jpeg "Open Street Map Commenting")

> 3. tagging some features 

![Open Street Map Tagging!](/pics/Open%20Street%20Map%20Tag%20Edit.jpeg "Open Street Map Tagging")

- Forking the Kartoza Handbook on GitHub

> ![Forking Kartoza Handbook!](/pics/Screenshot%20Forking%20Kartoza%20Handbook.jpeg  "Kartoza Handbook Forked")

- Get started with *[Markdown](https://www.markdownguide.org/ "Getting Started with Markdown")*
- Start with *[Markdown Basic Syntax](https://www.markdownguide.org/basic-syntax/ "Markdown Basic Syntax")* then move to *[Markdown Extended Syntax](https://www.markdownguide.org/extended-syntax/ "Markdown Extended Syntax")*

- Attending the Intern Hangout Meeting on Friday helped learn more about GitHub and Markdown
- Joining a Mapping Party helps to dive deep into cartography, and learn new tricks about developing and designing _maps_


### Glossary

**QGIS**

__Terminology__

***QGIS (Quantum Geographic Information System)*** : A free and open-source cross-platform desktop geographic information system application that supports creating, viewing, editing, printing, analysis, and publishing of geospatial data

***Symbology*** : The use of symbols to represent the features and attributes of a map layer. For example in a layer of trees, small green dots may be used to represent trees. The number of the dots can be varied to symbolize the trees populace. The _symbology_ of a layer is its visual appearance on the map.

***Labels*** : The textual information you can display on vector features or maps. They serve as a medium of communication between the creator of the map and the end user of the map.

***Layers*** :  It provides tools for creating GeoPackage, Shapefile, SpatiaLite, GPX format and Temporary Scratch layers (aka memory layers). since _QGIS_ allows one to create new layers in different formats.

***Raster Data*** : They are a grid of regulary sized pixels. Raster data are good for showing continually varying information. The size of pixels in a raster determines its spatial resolution. Raster images can contain one or more bands, each covering the same spatial area, but containing different information.

***Vector Data*** : The vector model represents the location and shape of geographic features using points, lines and polygons (and for 3D data also surfaces and volumes), while their other properties are included as attributes (often presented as a table in QGIS). It is usually used to store discrete features, like roads and city blocks.

**Git**

__Terminology__

***Git*** : Git is a distributed version control system that tracks changes in any set of computer files, usually used for coordinating work among programmers collaboratively developing source code during software development. Its goals include speed, data integrity, and support for distributed, non-linear workflows.

**GitHub**

__Terminology__

***Branch*** : Branches allow you to develop features, fix bugs, or safely experiment with new ideas in a contained area of your repository. You always create a branch from an existing branch. Typically, you might create a new branch from the default branch of your repository

***Stage*** : Implies that you have marked a modified file(s) in its (their) current version to go into your next commit snapshot.

***Commit*** : A commit, or "revision", is an individual change to a file (or set of files). When you make a commit to save your work, Git creates a unique ID (a.k.a. the "SHA" or "hash") that allows you to keep record of the specific changes committed along with who made them and when.

***Pull*** : A pull request let you tell others about changes you've pushed to a branch in a repository on GitHub. Once a pull request is opened, you can discuss and review the potential changes with collaborators and add follow-up commits before your changes are merged into the base branch.

***Push*** : The git push command is used to upload local repository content to a remote repository. Pushing is how you transfer commits from your local repository to a remote repo. It's the counterpart to git fetch , but whereas fetching imports commits to local branches, pushing exports commits to remote branches.

***Clone*** : When you clone a repository, you download the repository from GitHub.com to your local machine. Cloning a repository pulls down a full copy of all the repository data that GitHub.com has at that point in time, including all versions of every file and folder for the project.

***Fetch*** : In review, git fetch is a primary command used to download contents from a remote repository. git fetch is used in conjunction with git remote , git branch , git checkout , and git reset to update a local repository to the state of a remote.

***Fork*** : A fork is a copy of a repository that you manage. Forks let you make changes to a project without affecting the original repository. You can fetch updates from or submit changes to the original repository with pull requests.

***Head*** : The _HEAD_ in Git is the pointer to the current branch reference, which is in turn a pointer to the last commit you made or the last commit that was checked out into your working directory. That also means it will be the parent of the next commit you do.

***Index*** : The working or staging area of Git files that have been changed, added and deleted will be staged within the index until you are ready to commit the files. To see what is set in your Git index , run “git status” within your repository. The green files are staged and ready to commit, whereas the red files have not yet been added to staging for the next commit.

***Master / Main*** : It is the default primary branch of all repositories, all committed and accepted changes should be merged on the master branch. You can work directly from the master branch, or create other branches.

***Merge*** : It is Git's way of putting a forked history back together again. The git merge command lets you take the independent lines of development created by git branch and integrate them into a single branch.

***Origin*** : In Git, "origin" is a shorthand name for the remote repository that a project was originally cloned from. More precisely, it is used instead of that original repository's URL - and thereby makes referencing much easier. Note that origin is by no means a 'magical' name, but just a standard convention.

***Remote*** : A remote in Git is a common repository that all team members use to exchange their changes. In most cases, such a remote repository is stored on a code hosting service like GitHub or on an internal server. In contrast to a local repository, a remote typically does not provide a file tree of the project's current state.

