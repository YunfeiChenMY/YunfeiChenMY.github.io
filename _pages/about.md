---
permalink: /
title: "Academic Pages is a ready-to-fork GitHub Pages template for academic personal websites"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am currently a PhD student (class of 2021) in Computer Science and Technology at Central South University, with a long-term focus on cross-modal hashing retrieval and multi-agent systems. I have published multiple papers in SCI and CCF journals and participated in several National Key R&D projects. My PhD advisor is Professor Long Jun, Director of the Big Data Institute at Central South University (https://faculty.csu.edu.cn/longjun/zh_CN/index.htm). 长期担任KBS, NN, IPM, IEEE trans MM等等中科院一区期刊审稿人。

**1）Journal Articles / Conference Papers:**
[1]	**Yunfei Chen**, Jun Long, Zhan Yang, et al. Supervised Semantic-Embedded Hashing for Multimedia Retrieval[J]. Knowledge-Based Systems, 2024: 112023. 中科院一区 TOP
[2]	Jun Long, **Yunfei Chen**, Zhan Yang. Manifold based Semantic Similarity Reconstructing Hashing. CCF BigData 2024. Accept
[3]	**Yunfei Chen**, Jun Long, Zhan Yang, et al. Unsupervised Joint-Semantics Autoencoder Hashing for Multimedia Retrieval. ICONIP 2023. https://doi.org/10.1007/978-981-99-8073-4_25. CCF-C
[4] **Yunfei Chen**, Hongyu Lin, Jun Long, Zhan Yang. Hyper-graph Based Cross-modal Retrieval Hashing with Correlation and Robust Similarity Guide. ICONIP 2024.Accept CCF-C
[5]	**Yunfei Chen**, Yitian Long, Zhan Yang, Jun Long. Unsupervised Adaptive Hypergraph Correlation Hashing for Multimedia Retrieval. IEEE Transactions on Circuits and Systems for Video Technology. Under Review
[6] Jun Long, Junkun Hong, Zidong Wang, Tingxuan Chen, **Yunfei Chen**, Yang Liu. SPHASE: Multi-Modal and Multi-Branch Surgical Phase Segmentation Framework based on Temporal Convolutional Network[C]//2023 IEEE International Conference on Bioinformatics and Biomedicine (BIBM). IEEE, 2023: 586-593. CCF-B
[7] 龙军，邓茜尹，**陈云飞**，杨展*. 基于图卷积的无监督跨模态哈希检索算法[J]. 计算机工程与设计，已录用, 2023 (CCF-C)
[8] Liu Yang, Kaiting Zhang, Yinan Li, **Yunfei Chen**, Jun Long, Zhan Yang. S3ACH: Semi-Supervised Semantic Adaptive Cross-modal Hashing. International Conference on Neural Information Processing (ICONIP) (2023)(CCF-C, Full)


**2）Patents:**
[1]	龙军; 蒯明锦; 杨展; **陈云飞**. 用于多模态医学数据缺失的哈希编码方法、终端及介质. 公开号（授权）: CN116414867B.
[2]	杨柳; 张恺庭; 杨展; 龙军; **陈云飞**. 一种基于量化哈希编码的时空数据检索方法. 公开号（授权）: CN116414867B.
[3]	屠泽榕; 杨展; 龙军; 费洪晓; **陈云飞**. 一种基于联邦哈希学习的面向跨节点多模态检索方法. 公开号（授权）:CN115686868B.
[4] 龙军;蒯明锦;杨展;**陈云飞**. 用于多模态医学数据缺失的哈希编码方法、终端及介质, ZL202311474216.7. (已授权)

**3）projects:**
[1]	基于超算的跨网络大规模多源数据实时分析方法研究，国家自然科学基金，参与;
[2]	面向铁路科技管理全流程的查重系统方案研究，重大课题，参与;
[3]	地理空间智能核心技术与软件系统，国家重点研发计划（2021YFB3900902），参与；
[4]	湘雅医院(皮肤病)互联网医院远程问诊平台，长沙市科技重大专项（ KH2202005 ），参与。



A data-driven personal website
======
陈云飞Like many other Jekyll-based GitHub Pages templates, Academic Pages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

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
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
