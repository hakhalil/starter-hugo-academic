---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "A Task-Agnostic Machine Learning Framework for Dynamic Knowledge Graphs"
authors: [Nicholas Sendyk, Curtis Davies, Titus Priscu, Miles Sutherland, Atallah Madi, Kevin Dick, Hoda Khalil, Ala Abu Alkheir, and Gabriel Wainer]
date: 2022-011-15
doi: "10.5555/3566055.3566058"

# Schedule page publish date (NOT publication's date).
publishDate: 2023-01-31

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Proceedings of the 32nd Annual International Conference on Computer Science and Software Engineering"
publication_short: "CASCON '22"

abstract: "Many applications require well-structured and current information to enable downstream tasks. Knowledge graphs are a type of knowledge representation that effectively organize current information capturing elements and the relationships between them such that they can be queried and/or reasoned over in more advanced applications. A particular challenge is ensuring that an application-specific knowledge graph is both comprehensive and contains the most current representation, achieved through dynamic updating. Some available software frameworks for managing information as part of a data science pipeline are effective in collecting, labelling, and analysing textual data using natural language processing. Despite the utility of these frameworks, they can nonetheless be daunting for use by industry professionals and/or researchers who may not be familiar with the specifics of each tool. In this work, we present a generalized task-agnostic supervised machine learning framework that serves as a streamlined methodology for the creation and dynamic updating of knowledge graphs. A user needs only to define task-specific parameters allowing the tool to scrape data from the internet, generating a candidate corpus. The user may then provide sample annotations from the corpus to train task-specific natural language processing models to extract the relevant knowledge graph elements and the relationships connecting them. We demonstrate the utility of this framework for a case study seeking to build knowledge graph representations of merger and acquisition events between companies from scraped online articles reporting these instances. Our task-specific machine learning models achieve upwards of 99.2% F1 score evaluation metric on candidate web page classification and 81.5% F1 score on sentence-level extraction of entity relationships, demonstrating the promise of this framework.Our framework is freely available at: github.com/Checktr/tadkg"

# Summary. An optional shortened abstract.
summary: ""

tags: [data science, natural language processing, web scraping, machine
learning, knowledge graph updating]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf:
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source: https://dl.acm.org/doi/proceedings/10.5555/3566055
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
