 # Advanced Fisheries Economics Workshop February 5 - March 5 2021

Links to materials can be found here along with further instructions.

## Preparation

We will be using Jupyter notebooks and Python. 

The first-step is to click on the link at right and install [Anaconda](https://www.anaconda.com/distribution/)

Download and install the Python 3.7 version. You will need administrator rights on your computer to do this.

Also have a look at [Google Collaboratory](https://colab.research.google.com/) (you will need a [gmail account](https://accounts.google.com/signup/v2/webcreateaccount?hl=en&flowName=GlifWebSignIn&flowEntry=SignUp) to access this).

We will use [Zoom](https://zoom.us) for  classroom presentation and discussion, you will need to sign up for an account and downlaod the software. In addition to participate and receive assistance if you get stuck on something we will use [AnyDesk](https://anydesk.com/en). You will need to download and install this by following the instructions as they appear. AnyDesk will allow me to monitor your indiviual progress and assist you if you appear not to understand something or are falling behind.

## Philosophy

The approach we take is informed by a number of ideas, the first is that the practice of economics is largely a form of computation, the second it that analyses should be reproducible ([reproducible research](https://reproducibleresearch.net/)) and the third that when reporting the results of analyses, the emphasis should be on the written word rather than the computation ([literate programming](http://www.literateprogramming.com/)). Finally, the approach should be participative in the tradition of [R.L. Moore's approach to teaching mathematics](http://www.legacyrlmoore.org/).

## Location of particpants


[Location](https://www.google.com/maps/d/u/0/viewer?mid=18wL9f5dNoXIHSBoXMhi_u3qkkM7ErUcF&ll=-3.81666561775622e-14%2C149.12446502180342&z=1)


## Background

I recommend Preston McAfee, Tracy Lewis and Don Dale's [Introduction to economic analysis](https://www.kellogg.northwestern.edu/faculty/dale/ieav21.pdf) as background reading on general economics. Chapter 7 section 6 is on fisheries.

[National and regional fisheries economics workshop interactive tutorials](https://ffa-econ.shinyapps.io/econworkshop/) are also useful background.

Some Python links

[Python for economists](https://scholar.harvard.edu/files/ambell/files/python_for_economists.pdf)

[Kevin Sheppard, Introduction to Python for Econometrics, Statistics and Data analysis](https://www.kevinsheppard.com/files/teaching/python/notes/python_introduction_2019.pdf)

## References 

Arne Eide's [Introduction to Fisheries Economics](https://figshare.com/articles/Introduction_to_Fisheries_Economics/3784821#)
is a good reference. It uses Wolfram Language (Mathematica) for the exercises which is an alternative but less on-line support and help available. So we will use Python instead. [Google trends](https://trends.google.com/trends/explore?cat=174&date=all&q=%2Fm%2F05z1_,Mathematica,Excel,R,Julia%20programming%20language) partially answers why Python is a good choice.

Rognvaldur Hannesson *[The economics of fishing](https://www.amazon.com/gp/product/B08SR3N3KY/)*, Agenda Publishing; 1st edition (January 21, 2021). Easy reading general overview for interested readers.

David Whitmarsh *[Economic management of marine living resources:A practical introduction](https://www.amazon.com/gp/product/B008FZ0O7Q/)* Earthscan 2011.  Good introduction for practitioners.

The material covered will draw on a variety of sources inlcuding the following books and papers that will be referred to during the workshop.

*Intermediate texts* (upper level undergraduate)

- Jon Conrad, *[Resource Economics](https://www.amazon.com/Resource-Economics-Jon-M-Conrad-ebook/dp/B00FF76RAK/)*, Cambridge University Press; 2 edition (June 14, 2010) Chapters 1-3. Excel based textbook

- Larry Karp, *[Natural Resources as Capital](https://www.amazon.com/Natural-Resources-Capital-MIT-Press-ebook/dp/B077SVV5M8/)*, The MIT Press (November 17, 2017). 

- Anthony C. Fisher. [Lecture notes on resource and environmental economics](https://www.amazon.com/Resource-Environmental-Economics-Non-Market-Resources-ebook/dp/B08BXKVJM3), Springer 1st Edition, 2020.

- Ana Espinola-Arredondo, Felix Muñoz-Garcia *[Common pool resources](https://www.amazon.com/Common-Pool-Resources-Inefficiencies-Information-ebook/dp/B095KFF764/)* Cambridge University Press (October 21, 2021).

- Lee G. Anderson. *[The Economics of Fisheries Management](https://www.amazon.com/Economics-Fisheries-Management-Lee-Anderson/dp/1930665989/)*. Revised and enlarged edition.the John Hopkins University Press, 1977/1986/2004.

*Advanced texts* (Graduate level)

- Chen Xinjun et al. [Fisheries Resource Economics](https://doi.org/10.1007/978-981-33-4328-3) Springer. China Agriculture Press 2021. 

- Colin Clark. *[Mathematical Bioeconomics](https://www.amazon.com/Mathematical-Bioeconomics-Management-Renewable-Resources/dp/0471508837/)*. 2nd Edition John Wiley and sons, 1990.

- Jon Conrad and Colin Clark. *[Natural resource economics: Notes and problems](https://www.amazon.com/Natural-Resource-Economics-Notes-Problems-ebook/dp/B01MUHXUD0)*, Cambridge University Press (November 27, 1987). This text uses Basic for the computations.

- Jon Conrad and Daniel Rondeau, *[Natural Resource Economics: Analysis, Theory, and Applications](https://www.amazon.com/Natural-Resource-Economics-Analysis-Applications-ebook/dp/B083M1L7SM/)*, Cambridge University Press 
(February 29, 2020). This text also uses Wolfram Language (Mathematica).

- P. Dasgupta and G. Heal. *Economic theory and exhaustible resources*. Cambridge University Press, Cambridge University Press (March 31, 1980).

- L. Gronbaek, et al. *Game theory and fisheries management: Theory and application*. Springer; 1st ed. 2020 edition (February 18, 2020).

-  P.A. Neher. *Natural resource economics: Conservation and exploitation*. Cambridge University Press, 1990.

- M. Majumdar *[Sustainability And Resources: Theoretical Issues In Dynamic Economics](https://www.amazon.com/gp/product/B08534FTYG)* World Scientific 2020. Some chapters at intermediate level.

- M. Mangel. *Decision and control in uncertain resource systems*, Academic Press, 1985. Adavanced text uses stochastic methods

- A. Xepapadeas *[Advanced Mathematical Methods in Environmental and Resource Economics](https://www.amazon.com/gp/product/B0BL6YNLNB/)* World Scientific, 2023. Advanced text covers a variety of methods.

## Exercises

Exercises will be completed in Jupyter notebooks. Jupyter notebooks are interactive mathematical notebooks that are based on the idea of literate programming, where the words and comments are just as important as writing computer code. Think of them as like Word documents that can do calculations and plot graphs.

## Week 1

### Introduction

[Slides 1](https://nbviewer.jupyter.org/github/fdd-eiu/afew/blob/main/afew-present-1.ipynb)

[Notebook 1](https://nbviewer.jupyter.org/github/fdd-eiu/afew/blob/main/afew-notebook-1.ipynb)


### Renewable resources and population dynamics

[Slides 2](https://nbviewer.jupyter.org/github/fdd-eiu/afew/blob/main/afew-present-2.ipynb)

[Notebook 2](https://nbviewer.jupyter.org/github/fdd-eiu/afew/blob/main/afew-notebook-2.ipynb) 
[Solutions](https://nbviewer.jupyter.org/github/fdd-eiu/afew/blob/main/afew-notebook-2-solutions.ipynb)

[Slides 3](https://nbviewer.jupyter.org/github/fdd-eiu/afew/blob/main/afew-present-3.ipynb)

[Notebook 3](https://nbviewer.jupyter.org/github/fdd-eiu/afew/blob/main/afew-notebook-3.ipynb)

[Slides 4](https://nbviewer.jupyter.org/github/fdd-eiu/afew/blob/main/afew-present-4.ipynb)

## Week 2

### Static Open Access Model


[Slides 5](https://nbviewer.jupyter.org/github/fdd-eiu/afew/blob/main/afew-present-5.ipynb) Gordon-Schaefer model

[Slides 6](https://nbviewer.jupyter.org/github/fdd-eiu/afew/blob/main/afew-present-6.ipynb) Empirical bio-economic modelling

- Some alternative models

- Zonal affiliation

- licensing models

## Week 3

### Dynamic fisheries models

- dynamic open access model

- dynamic optimization

- Capital Theoretic Model

- Most rapid approach path

- impact of discounting

- Coastal state vs distant water nations *might postpone to the following week)

## Week 4

TBA possibly game theory

- selected material from Gronbaek et al. 

## Week 5

Selected topics or own projects


## Feedback form

Please complete the feedback form below!

[Feedback form](https://forms.gle/KZ1zNZhr5Q7kmneZ6)






















