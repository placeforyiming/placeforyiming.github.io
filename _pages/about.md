---
permalink: /
title: "Current PhD Experiences"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm a PhD candidate supervised by [Dr. Xinming Huang](https://users.wpi.edu/~xhuang/) at ECE Department of Worcester Polytechnic Institute. I also spent half a year to work at iRobot as an intern supervised by [Dr. Stefan Zickler](https://scholar.google.com/citations?user=G_vOcFUAAAAJ&hl=en&oi=ao). During my PhD, I have been working on building various robotic vision systems to meet the requirement of my fundings. Specifically:
<ul>
  <li>I built a camera-centered online 3D semantic occupancy grid system for autonomous cars via solving the <b>depth completion task</b>. </li>
  <li>The counterpart LiDAR-centered system is built by solving the <b>point cloud panoptic segmentation task</b>. </li>
  <li>For UAV and geo-survey, I proposed a pixel-wise geo-localization system to align the onboard camera image with satellite maps by extending tradition Lucas-Kanade with neural networks (<b>deep homography task</b>).</li>
   <li> At iRobot, I built a label-free system to train a monocular depth prediction network by combining existing 3D reconstruction system with <b>self-supervised depth prediction task</b>.</li>
</ul>
 
 Besides those research projects, I also implemented several popular robotic vision models on demand, such as the 3D detector AVOD, the 2D YOLO series, and panoptic-Deeplab etc. Several of my research papers have been published on well-recognized conferences and journals, like CVPR and IEEE Robotic and Automation Letter. Some of my papers are still under review. Please see the Portfolio&Pub for details.
   

Master of Systems Science at BNU
======
I spent two years to get the master degree of systems science at Beijing Normal University. I published a good data modeling paper as well as undertook several industiral projects.   

Bachelor of Physics at LZU
======
My undergraduate life at Lanzhou University is pure and enjoyable. I majored in math for two years, then transfered to physics for three years. This is an important period for me that I learned not only the scientific knowledge but also how human understand the world. More specific, I discard the idea that the physical world is determinable with universal truth and accept the fundamental uncertainty with inevitable observers' bias.        

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
