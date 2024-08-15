---
permalink: /
title: "Welcome!"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

## News

I'll be joining the Machine Learning Department at Carnegie Mellon University, beginning in January 2025! And, accordingly, <span style="color:#C41230">**I am  actively recruiting students applying for PhD programs this year to begin in Fall of 2025!**</span> See below for my own research interests, and for what I'm looking for in prospective students.


## Research Interests

My research focuses on learning in sequential, interactive or dynamic settings. This includes everything from reinforcement learning, to prediction in control systems, to robotic agents. At the moment, I'm very excited about how large AI models might change how we think about these problems. For example, how do [generative model architectures like diffusion models enable robots to learn general behaviors](https://arxiv.org/abs/2307.14619)? Or how can we develop new [ deep learning methods for world modeling, video prediction, decision making](https://arxiv.org/abs/2407.01392) and more? And might [certain types of deep learning models be able to leverage diverse training experience to explore their environments and rapidly improve their own performance]() (this paper is not out just yet :)

My current interests span the gamut from mathematical to practical. But all of my research is informed by years thinking like a theorist; this research ranged broadly across topics in adaptive sampling, multi-arm bandits, complexity of convex and non-convex optimization,  reinforcement learning, learning in linear and nonlinear dynamical systems, and fairness in machine learning.  

## Student Recruiting

The best way to work with me is to *apply to a Masters or PhD program in the School of Computer Science at Carnegie Mellon*; I will recruit mostly from the [Machine Learning Department](https://ml.cmu.edu) and [Robotics Institue](https://ri.cmu.edu) PhD applications. I'm particularly excited about students who love to think deeply and hatch truly new (sometimes crazy) ideas, and am looking for candidates across the theory-to-practice spectrum. 
An ideal applicant should come in with at least one core strength (e.g. mathematical problem solving, software engineering,  deep learning research), and be eager to develop other abilities as the PhD continues.
I strongly encourage students who come from a diverse set of backgrounds to apply, including racial, gender,   sexual and religious identities, political beliefs, socioeconomic and disability statuses, and non-traditional educational/professional paths. 

## Selected Publications

<div style="font-size:0.9em;">
{% for post in site.publications reversed %}
  {% unless post.selected == true%}
    {% continue %}
  {% endunless %}
  <a href="{{post.paperurl}}">{{post.title}}</a> <p style="margin:-2px;">{{post.authors}}. <i>{{post.venue}}</i>, 
      <span style="color:#C41230"><b>{{post.award}}</b></span>
    {{post.year}}.<br/></p ><p style="margin:10px;"></p> 
{% endfor %}
</div>

## Selected Awards

<div style="font-size:0.9em;">
{% for post in site.awards reversed %}
  {% unless post.selected == true%}
    {% continue %}
  {% endunless %}
  <b>{{post.title}}</b>.
  <a href="{{post.paperurl}}">{{post.papername}}</a> <i>{{post.venue}}</i>,
    {{post.year}}.<br/><p style="margin:10px;"></p> 
{% endfor %}
</div>





## Bio

Hi, I'm Max. I started my academic journey as a math major at Princeton University, where I was fortunate enough to do research with [Sanjeev Arora](https://www.cs.princeton.edu/~arora/) and [David Blei](http://www.cs.columbia.edu/~blei/">) (who taught at Princeton at the time). I went on to do a PhD focusing on theoretical questions in Machine Learning in the EECS department at UC Berkeley, co-advised by [Ben Recht](http://www.eecs.berkeley.edu/~brecht) and [Michael Jordan](http://www.cs.berkeley.edu/~jordan/).  I also worked with, and was closely mentored by, [Elad Hazan](https://ehazan.com/) at Princeton and [Kevin Jamieson](https://homes.cs.washington.edu/~jamieson/about.html), now at University of Washington. 

I spent a good chunk of my PhD thinking about mathematical questions governing how and under what conditions one can learn to predict and control dynamical systems. But as the PhD progressed, I wanted to understand what the relevant challenges in pratical applications, especially as many larger AI models were starting to overcome hurdles once thought insurmountable. I was lucky to be able to postdoc in Russ Tedrake's [Robot Locomotion Group](https://locomotion.csail.mit.edu/people.html) in the [EECS Department](https://www.eecs.mit.edu) at MIT, and this is what opened me up to my ongoing curiosity about robot learning (both practical and mathematical).

A lot of folks in this field like spending time outdoors, and I respect that. But I'm more of an inside person - I like reading, listening to music, I play saxophone and (pretend to) play jazz piano, and love a good dinner party. Over the pandemic I got addicted to car YouTube; not sure if I have recovered (?). 


<!--About Me.
======
This is the front page of a website that is powered by the [Academic Pages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the respository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. You can fork [this repository](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and markdown files, add your own PDFs and other content, and have your own site for free, with no ads! An older version of this template powers my own personal website at [stuartgeiger.com](http://stuartgeiger.com), which uses [this Github repository](https://github.com/staeiou/staeiou.github.io).

A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, Academic Pages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over -- just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

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
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might 
also be helpful.
--->
