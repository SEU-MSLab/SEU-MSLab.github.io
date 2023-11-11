---
permalink: /
title: "Microwave System Lab @ Southeast University"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
Yu, Chao (余超), Professor, Ph.D's Advisor
======
We are actively recruiting PhD and Master students. Self-motivated students with relevant research interest (Digital Predistortion, power Amplifier design, RF front-ends, etc.) are highly encouraged to contact me via email.

** Short Bio **
### State Key Laboratory of Millimeter Waves, Southeast University, China

Professor           (Apr. 2021 to present)
Associate Professor (Jun. 2015 to Apr. 2021)

### University College Dublin, Ireland

Researcher          (Mar. 2014 to May 2015)
PhD in Electrical Engineering, 2014

### Southeast University, China
Master in Electrical Engineering, 2010
Bachelor of Information Engineering, 2007

** Research Area **
Software and hardware co-design of microwave systems
Design of 5G mmWave massive MIMO phased-array systems
Linearization techniques for microwave/mmWave PAs

** Honors & Awards **
* IEEE MTT-S Microwave Prize
* National Science Fund for Excellent Young Scholars (国家优青)
* National Scholarship for Outstanding Self-Funded Foreign Students (国家优秀留学生大奖)

** Teaching **
RF Circuit Modeling and CAD (Bilingual, Undergraduate Course)

Research Topics
======
Our research focuses on RF front-ends for wireless communications, including the design of RF hardware and algorithms. On one hand, massive multiple-input multiple-output (massive MIMO) technology has been widely used in the fifth-generation mobile communication systems (5G) in order to achieve higher data rates. On the other hand, the available spectrum in sub-6 GHz has become increasingly scarce, which boosts the development of millimeter-wave (mmWave) transmission. Therefore, mmWave massive MIMO technology has been a competitive and attractive candidate in 5G. It can be applied in many fields such as radar for automobiles, mmWave imaging, inter-satellite and satellite-ground communication links. In view of this, we aims at better performance of mmWave massive MIMO front-ends, which is divided into two parts: **hardware** and **algorithms**. 

A data-driven personal website
======

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
