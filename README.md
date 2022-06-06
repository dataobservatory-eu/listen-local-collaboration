# README: Listen Local Collaboration Manual

[![ListenLocal](https://img.shields.io/badge/Developd%20by-Listen%20Local-007CBB.svg)](https://music.dataobservatory.eu/usecase/listen-local/) Listen Local is an open collaboration for artists, fans, managers, developers to provide alternatives to connect local audiences with local artists through locally relevant music recommendations and findings. As a project of the  Digital Music Observatory it aims to make big data work for small labels and self-released artists, and to make algorithms work for and not against them.

[![DMO](https://img.shields.io/badge/Powered%20by-Digital%20Music%20Observatory-4EC0E4.svg)](https://music.dataobservatory.eu/) A highly automated, open source, open data observatory concept that links public datasets in order to provide a comprehensive view of the European music industry. The Digital Music Observatory is an open collaboration project initated by Reprex in cooperation with its contributors.

[![Github commits](https://img.shields.io/github/commit-activity/m/dataobservatory-eu/listen-local-collaboration)](https://github.com/dataobservatory-eu/listen-local-collaboration/)

[![FAQ](https://img.shields.io/static/v1?label=FAQ&message=Ask%20a%20Question&color=4EC0E4)](https://github.com/dataobservatory-eu/listen-local-collaboration/projects/)
[![issues](https://img.shields.io/static/v1?label=FAQ&message=Check%20Open%20Questions%20First&color=DB001C)](https://github.com/dataobservatory-eu/listen-local-collaboration/issues?label=open)



## Folders

**root** - Do not save any new files here other than `.bib` bibliography files in the root directory unless you are familiar with `bookdown`. Mainly `yml` files for markdown conversions and `Rmd` Rmarkdown source files. 

**bib** - please save here individual BibTex entries.  The consolidated entries will should be placed in one of the main `.bib` files in the root folder. The pandoc / knitr / RStudio workflow can have hickuups with bib files, so try to save individual files first in `bib/xyz.bib`. The bibliographic entries must be added in a way making sure that at least the title={}, author={} and the year={} fields are not empty, i.e. if there is only a date ={2022-05-06} field, you create a year = {2022} field, too.

**not_included** - user's scrap directory, excluded by `.gitignore`.  Please put your non-synchronized scaps and code doodles here.

**data-raw** - data as downloaded, received, as a starting point of our reproducible work. You will find here 5 CAP surveys.

**R** - R code written for the publications.  It is better to write stand-alone R codes, and put final 'chunks' into the `.Rmd` files.

**data** - Final data outputs that will be placed in the articles.


## Contributor Covenant Code of Conduct

You must abide the [CONTRIBUTOR COVENANT CODE OF CONDUCT](https://www.contributor-covenant.org/version/2/1/code_of_conduct/) pledging to make participation in our community a harassment-free experience for everyone, regardless of age, body size, visible or invisible disability, ethnicity, sex characteristics, gender identity and expression, level of experience, education, socio-economic status, nationality, personal appearance, race, caste, color, religion, or sexual identity and orientation. (See [translations](https://www.contributor-covenant.org/translations/) and [FAQ](https://www.contributor-covenant.org/faq/).)
