---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Ziqiang Yu, Ph.D., currently a Professor at the School of Computer and Control Engineering, Yantai University. He serves as Deputy Secretary-General of the 'Intelligent Services Technical Committee' of the Chinese Association for Artificial Intelligence (CAAI), Executive Committee Member of the Database Technical Committee of the China Computer Federation (CCF), Executive Committee Member of the CCF Artificial Intelligence and Pattern Recognition Technical Committee, Council Member of the ACM SIGSPATIAL China Chapter, and Executive Council Member of the Shandong Association for Artificial Intelligence. He taught at the University of Jinan from 2015 to 2020, worked as a Visiting Scholar at the University of York from 2018 to 2019, and has been teaching at Yantai University since 2020. His primary research interests lie in data intelligent management and analytics, including data intelligence computing, video cross-modal retrieval, graph data management, and distributed computing. He has led various research projects funded by the National Natural Science Foundation of China (General Program and Young Scientists Program), the CCF-Huawei Populus euphratica Fund, the Key Research and Development Program of Shandong Province, and the Natural Science Foundation of Shandong Province (General Program), among other national, provincial, and leading industry research initiatives. He has published over 30 papers in top-tier CCF-A international conferences and journals such as SIGMOD, VLDB, ICDE, SIGIR, and TKDE. He serves as an Editorial Board Member for Frontier of Computer Science (CCF-B journal), Proceeding Chair for SIGKDD 2025 (CCF-A conference), a reviewer for CCF-A journals including VLDB Journal and TKDE, and a Program Committee Member for top international conferences such as SIGKDD, AAAI, and CIKM.

Work Experience
======
- **2020.02 - Present**, Professor, Master's Supervisor, Yantai University
- **2018.04 - 2019.04**, Assistant Researcher, York University
- **2015.07 - 2020.01**, Lecturer, Jinan University

Research Interests
======
- **AI and Database Systems**: Leveraging database theories and techniques to enhance the training, reasoning, and generation capabilities of AI models.

- **Spatio-Temporal Data Management and Analytics**: Developing efficient methods for querying, analyzing, and predicting large-scale spatio-temporal data.

- **Structured Video Retrieval**: Integrating structured query techniques with Large Language Models (LLMs) to improve the efficiency and accuracy of cross-modal video retrieval.

- **Distributed Computing for Massive Data**: Designing scalable distributed solutions for efficient search and processing of spatio-temporal and high-dimensional data.

Our research findings have been published in premier international conferences and journals in the field of data science, including **SIGMOD, VLDB, ICDE, SIGIR, and TKDE**, which represent the highest level of research in the discipline. We warmly welcome highly motivated undergraduate and graduate students with strong academic aspirations and research interests to join our research group.

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
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
