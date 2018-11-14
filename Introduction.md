#### Hello and welcome to the Data Science Beginners Guide 

I originally built this repository so that It will be helpful for my process of learning. Through building the repo I realized that other people might be also be interested in this content - so I have tried to curate content on data science topics, high quality resources to learn from, and relevant blog posts.  

The intended goal was to cover more than just the technical component  of data science.  Data Science as a discipline is still relatively fresh and many business are learning how to properly integrate and structure those teams and also proper understanding the value proposition that data science can provide.

As a result I also tried to find topics that cover building data science teams, business practices, use-cases, product metrics and data science career paths.  

This is a constant work in progress and I hope to refactor and update in some kind of meaningful time frame.

If you find this resource helpful - please send it around to other people or you can [Connect](https://www.linkedin.com/in/iamsivab/), share it on linkedIn, twitter, Facebook, add it to Quora or just send me a note.   Good luck, I hope this helps you find what you are looking for now, or in the future.

# Table Of Contents
1. [Data Science Getting Started](#data-science-getting-started)
  * [Start](#start)
  * [Data Science Courses](#data-science-courses)

2. [Data Pipeline & Tools](#data-pipeline--tools)
  * [Python](#python)
  * [Data Structures & CS topics](#data-structures--cs-topics)
  * [Statistics](#statistics)
  * [Stats/Engineering Libraries](#statsengineering-libraries)
  * [Databases/Frameworks](#databasesframeworks)
  * [Data Acquisition](#data-acquisition)
  * [Processing & EDA](#processing--exploratory-data-analysis)
  * [Machine Learning](#machine-learning)
    * [Machine Learning Theory](#machine-learning-theory)
    * [Deep Learning](#deep-learning)
    * [Model Selection](#model-selection)
    * [Model Evaluation](#model-evaluation)
    * [Feature Engineering](#feature-engineering)
  * [Additional Tools or Processes](#additional-tools-or-processes)
  * [Data Visualization](#data-visualization)
  * [ipython Notebook Tutorials](#ipython-notebook-tutorials)
  * [Data Sources](#data-sources)
  * [New Data Tools](#new-data-tools)

3. [Product](#product)
  * [Product Metrics](#product-metrics)
  * [Team Communication & Business Tools](#team-communication--business-tools)  
  * [Best Practices](#best-practices)

4. [Career Resources](#career-resources)
  * [Data Science Career Path](#data-science-career-path)
  * [Types of Data Scientists](#types-of-data-scientists)
  * [Data Science Applications/Use Cases](#data-science-applicationsuse-cases)
  * [Data Science Websites/Books](#data-science-websitesbooks)
  * [Data Science Meetups in the Bay Area](#data-science-meetups-in-the-bay-area)
  * [Data Science Blogs](#data-science-blogs)
  * [Data Science Conferences](#data-science-conferences)
  * [Data Science Presentations](#data-science-presentations)
  * [Relevant Business Processes](#relevent-business-processes)

5. [Open Source Data Science Resources](#open-source-data-science-resources)
  * [Additional Open Source Content](#other-open-source-data-science-content)
  * [Auxiliary Content & Apps](#auxiliary-content--apps)
6. [About Me](#about-me)

## Data Science Getting Started
Data Science is a multidisciplinary field covering at the very minimum - statistics, programming, machine learning [Drew Conway's venn diagram](http://drewconway.com/zia/2013/3/26/the-data-science-venn-diagram) or [Cheat Sheet of a Modern Data Scientist](http://www.marketingdistillery.com/2014/08/30/data-science-skill-set-explained/).  These topics are covered throughout this repo.  I personally find the best way to learn a topic is to get my hands dirty quickly - with that in mind I would get to work in python and then implement different tools or theory into my toolkit as they are understood.  If you haven't used python before I would strongly urge you to use the codecademy course to familiarize yourself with the content and how to program.  Good luck and have fun.

A note about order - I framed the contents in the Pipeline & Tools section order of the data pipeline starting with acquisition, exploratory data analysis, cleaning data, model section & evaluation and then visualization.

### Start
* [Data Science Pipeline](http://machinelearningmastery.com/wp-content/uploads/2014/05/Overview-of-the-Applied-Machine-Learning-Process.png) - Detailed overview of data pipeline from MachineLearningMastery.com
* [Intro to ipython](https://github.com/ipython/ipython/wiki/A-gallery-of-interesting-IPython-Notebooks/_edit#entire-books-or-other-large-collections-of-notebooks-on-a-topic) - A curation of Ipython Notebooks great for introductory level to python, programming, comp sci, data science and other topics.
* [How do I Become a Data Scientist?](http://www.quora.com/How-do-I-become-a-data-scientist) - Some more great starting points from William Chen.

### Data Science Courses:
* [Coursera](https://www.coursera.org/specialization/jhudatascience/1) - Data Science Specialization at Coursera - many other courses available as well.
* [Udacity](https://www.udacity.com/courses#!/data-science) - Online MOOCs that are the Data Science related courses. by I
* [Data Science Bootcamps](http://yet-another-data-blog.blogspot.com/2014/04/data-science-bootcamp-landscape-full.html) - A collection of all bootcamps currently on the market as of April 5, 2014 by Ikechukwu Okonkwo.
* [Coursera Machine Learning Course](https://www.coursera.org/course/ml) - Andrew Ng's pinnacle Machine Learning course.
* [Edx](https://www.edx.org/course/mitx/mitx-6-00-2x-introduction-computational-2836#.VEANx9TF-tw) - EDX courses related to data science.

## Data Pipeline & Tools

###Python
Python is my workhorse language specifically as it has many data science and statistic library, the ability to work in production environments, and work on other problems outside of data science.  There are many other languages that could be useful but are not covered here: Julia, R, Cython, Pig, Scala, Java, etc.

* [Python @ Codecademy](http://www.codecademy.com/en/tracks/python) - If you have never used Python, right this way..
* [The Python Wiki](https://wiki.python.org/moin/FrontPage) - Good resource with lots of info about Python.
* [Python for Data Science Tutorial - Kaggle](https://www.kaggle.com/wiki/GettingStartedWithPythonForDataScience) - Stepping into Data Science with Kaggle and installing some libraries.
* [Introduction to Data Processing with Python](http://opentechschool.github.io/python-data-intro/) - Just as the name says - some introductory level information and exercises.
* [Git tutorial](https://try.github.io/levels/1/challenges/1) - Git for Version Control.  Simple tutorial for Git from Github.
* [Git Tips](http://www.alexkras.com/19-git-tips-for-everyday-use/) - 19 git tips for everyday use.
* [Anyone Can Code](http://dhruvbird.com/61.html) - Languages, tutorials, cheat sheets, algorithms and data structures

#### Data Structures & CS Topics
* [Algorithms & Data Structures](http://www.bogotobogo.com/Algorithms/algorithms.php) - Binary trees, hash tables, linked lists, big(O) notation and more.
* [Algorithm & Data Structures](http://interactivepython.org/courselib/static/pythonds/index.html) - Well organized detailed and digestible site full of content covering data structures, algorithms, recursion and assignments!
* [Big O Notation](http://interactivepython.org/courselib/static/pythonds/AlgorithmAnalysis/BigONotation.html) - Great details and visual of big-O notation.
* [Visualizations of Data Structures](http://www.cs.usfca.edu/~galles/visualization/Algorithms.html) - Collection of different algorithms (graph problems) and data structures (queues, heaps, hashes) that walks through the visualization to get a better intuitive understanding. 
* [Data Structures CheatSheet & Big Oh Notation](http://bigocheatsheet.com/)
* [Data Structures CheatSheet -smaller more readable](https://www.clear.rice.edu/comp160/data_cheat.html)
* [Coursera: Stanford Algorithms Design & Analysis ](https://class.coursera.org/algo-006) - Course on algorithm design & analysis

####Statistics
Some primers on understanding statistics and other resources to get a deeper understanding.
* [Statistics Without the Agonizing Pain](https://www.youtube.com/watch?v=5Dnw46eC-0o) - John Rauser's really great video on statistics - funny and engaging with a good message.
* [Probability Programming and Bayesian Methods for Hackers](http://nbviewer.ipython.org/github/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/blob/master/Prologue/Prologue.ipynb) - full book all online through ipython notebooks.
* [Probabilistic Programming and Bayesian Methods for Hackers](https://github.com/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers) - Github Repo for the book above.
* [Statistics Cheat Sheet in Ipython Notebook](http://nbviewer.ipython.org/url/trust.sce.ntu.edu.sg/~gguo1/blogs/Statistics/Statistics.ipynb)
* [The only probability Cheatsheet you'll ever need](https://bayesrule.files.wordpress.com/2014/07/probability_cheatsheet_140718.pdf) - Self explanatory - (thanks William Chen @ http://datastories.quora.com/) for pointing me this great cheat sheet out - wish I had that back at college.
* [Khan Academy: Statistics](https://www.khanacademy.org/#statistics) - Tons of videos to help learn statistics concepts.
* [Statistical Distributions in iPython Notebook]

This Repository was Inspired From (https://www.github.com/jonathan-bower/DataScienceResources)
