+++
# Date this page was created.
date = 2019-01-20T00:00:00

# Project title.
title = "Student Teacher Evaluation Visualization (STEV) at OU"

# Project summary to display on homepage.
summary = "Built a web app to allow students to visualize OU course evaluations and professor reviews."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "projects/STEV.jpeg"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["Web-Dev"]

# Optional external URL for project (replaces project detail page).
external_link = "https://evals.info"

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
# [header]
# image = "projects/commuter_icon.jpeg"

# caption = "My caption :smile:"

+++
**[Link to Website](https://ou.evals.info)**

After each semester, OU students fill out course evaluations for each of their courses and professors. The review information is publicly available, but is shared in pdf files on [the OU website](http://www.ou.edu/provost/course-evaluation-data). This makes it very difficult for prospective students to use the course reviews to inform their enrollment decisions, because parsing through the hundreds of posted pdf files to find the desired information about the course or instructor is nearly impossible. My friends Zach Schuermann, Joe Lovoi, and I have scraped this data into a database and built a web app to allow much easier visualization of the course ratings and comparison between courses.  We're storing the data in **MongoDB**, with api web servers built in **Flask** and the frontend visualization framework developed in **React**. Keep up with our status on [our Github page](https://github.com/stev-ou). Our end goal is to be able to integrate our developed web app with the OU website and to give students easier access to this valuable data.

<br>