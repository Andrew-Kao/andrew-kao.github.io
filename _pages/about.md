---
permalink: /
title: "Andrew Kao"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hello! I am a PhD student in Economics at Harvard. My current research interests include political economy, artificial intelligence, and development. I am also a affiliate at the [Center for American Political Studies](https://caps.gov.harvard.edu/). I graduated from the University of Chicago in 2020 with a BS in computational and applied math and a BA in economics. My CV is located [here](https://andrew-kao.github.io/files/Andrew_Kao_CV_A_2023-06-11.pdf).

## Research

### Publications
- ["AI-tocracy"](https://andrew-kao.github.io/files/aitocracy_20221025.pdf) with Martin Beraja, David Yang, and Noam Yuchtman  — _Quarterly Journal of Economics_, August 2023 
    - Press: [CSIS](https://bigdatachina.csis.org/the-ai-surveillance-symbiosis-in-china/)
    - <a href="#!" class="btn" onclick="show_aitocracy()">Abstract</a>
<div id="aitocracy" class="notice--info" style="display:none">
  Recent scholarship has suggested that artificial intelligence technology and autocratic regimes may be mutually reinforcing. We test for such a mutually reinforcing relationship in the context of facial recognition AI in China. To do so, we gather comprehensive data on AI firms and government procurement contracts, as well as on social unrest across China during the last decade. We first show that autocrats benefit from AI: local unrest leads to greater government procurement of facial recognition AI as a new technology of political control, and increased AI procurement indeed suppresses subsequent unrest. We then show that AI innovation benefits from autocrats’ suppression of unrest: the contracted AI firms innovate more both for the government and commercial markets, and are more likely to export their products; and non-contracted AI firms do not experience detectable negative spillovers. Taken together, these results suggest the possibility of sustained AI innovation under the Chinese regime: AI innovation entrenches the regime, and the regime’s investment in AI for political control stimulates further frontier innovation.
</div> 

### Working papers
- "Exporting the Surveillance State via Trade in AI" with Martin Beraja, David Yang, and Noam Yuchtman 
  - Brookings Center on Regulation and Markets [working paper](https://www.brookings.edu/research/exporting-the-surveillance-state-via-trade-in-ai/) (January 2023)
  - Press: [Wired](https://www.wired.com/story/china-is-the-worlds-biggest-face-recognition-dealer/)
  - <a href="#!" class="btn" onclick="show_exportai()">Abstract</a>
<div id="exportai" class="notice--info" style="display:none">
  What are the international ramifications of China’s emergent leadership in facial recognition AI? We collect global data on facial recognition AI trade deals and document two facts. First, we show that China has a comparative advantage in this surveillance technology. It is substantially more likely to export facial recognition AI than other countries, and particularly so as compared to other frontier technologies. This comparative advantage may stem in part from the Chinese government’s demand for the technology to support its surveillance state — a form of “home-market” effect — as well as Chinese firms’ access to large government datasets. Second, we find that autocracies and weak democracies are more likely to import facial recognition AI from China, in particular those lacking domestic AI investment or experiencing political unrest. No such political bias is observed in AI imports from the US or in imports of other frontier technologies from China. To the extent that China may be exporting its surveillance state via trade in AI, this can enhance and beget more autocracies abroad. Regulations of AI trade should thus be framed around regulations on products with global externalities.
</div> 

### Works in progress
- ["Seeing is Believing: Identity, Inequality, and the Impact of Television on the Hispanic Achievement Gap"](https://andrew-kao.github.io/files/sltv_draft.pdf)   [[slides](https://andrew-kao.github.io/files/sltv_slides.pdf)]



### Policy Articles
- “Autocratic AI dystopias: From science fiction to social science fact” with Martin Beraja, David Yang, and Noam Yuchtman. [VoxDev column](https://voxdev.org/topic/institutions-political-economy/autocratic-ai-dystopias-science-fiction-or-social-science-fact) (May 2023)
- “Autocratic AI dystopias: From science fiction to social science fact” with Martin Beraja, David Yang, and Noam Yuchtman. [VoxEU column](https://voxeu.org/article/autocratic-ai-dystopias-science-fiction-social-science-fact) (December 2021)



<!-- SCRIPTS -->

<script type="text/javascript">
  function show_aitocracy() {
  var x = document.getElementById("aitocracy");
  if (x.style.display === "none") {
    x.style.display = "block";
  } else {
  x.style.display = "none";
  }
} 

function show_exportai() {
  var x = document.getElementById("exportai");
  if (x.style.display === "none") {
    x.style.display = "block";
  } else {
  x.style.display = "none";
  }
} 
</script>



<!-- ---
permalink: /
title: "academicpages is a ready-to-fork GitHub Pages template for academic personal websites"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

This is the front page of a website that is powered by the [academicpages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the respository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. You can fork [this repository](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and markdown files, add your own PDFs and other content, and have your own site for free, with no ads! An older version of this template powers my own personal website at [stuartgeiger.com](http://stuartgeiger.com), which uses [this Github repository](https://github.com/staeiou/staeiou.github.io).

A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, academicpages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

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
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
 -->