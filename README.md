# cs599-fall2019

## papers for student presentations

* [On optimal multiple changepoint algorithms for large data](https://link.springer.com/article/10.1007/s11222-016-9636-3)
* [Complexity analysis of the Lasso regularization path](https://arxiv.org/abs/1205.0079)
* [Minimizing finite sums with the Stochastic Average Gradient](https://arxiv.org/abs/1309.2388)
* [Fast Iterative Shrinkage Thresholding for Linear Inverse Problems](https://epubs.siam.org/doi/abs/10.1137/080716542)
* [Optimizing search engines using clickthrough data](https://dl.acm.org/citation.cfm?id=775067)
* [Group lasso with overlap and graph lasso](http://www.machinelearning.org/archive/icml2009/papers/471.pdf)
* [Block-coordinate Franck-Wolfe Optimization for Structural SVMs](https://arxiv.org/abs/1207.4747)
* [Latent dirichlet allocation](http://www.jmlr.org/papers/v3/blei03a.html)
* [Supervised dictionary learning](http://papers.nips.cc/paper/3448-supervised-dictionary-learning)
* [Convolutional kernel networks](http://papers.nips.cc/paper/5348-convolutional-kernel-networks)
* [Gaussian process kernels for pattern discovery and extrapolation](https://arxiv.org/abs/1302.4245)
* [Character-level convolutional networks for text classification](http://papers.nips.cc/paper/5782-character-level-convolutional-networks-for-text-classifica)
* [Gradient-Based Learning Applied to Document Recognition](http://yann.lecun.com/exdb/publis/pdf/lecun-98.pdf)
* [Regularization paths for generalized linear models via coordinate descent](https://www.jstatsoft.org/article/view/v033i01)
* [XGBoost: A Scalable tree boosting system](https://dl.acm.org/citation.cfm?id=2939785)
* [A decision-theoretic generalization of on-line learning and an application to boosting](https://www.sciencedirect.com/science/article/pii/S002200009791504X/pdf?md5=e471323f84c2764746c94ba206a9bc47&pid=1-s2.0-S002200009791504X-main.pdf&_valck=1)
* [Multivariate adaptive regression splines](https://projecteuclid.org/euclid.aos/1176347963)
* [Greedy function approximation: a gradient boosting machine](https://www.jstor.org/stable/2699986?seq=1#page_scan_tab_contents)
* [Least Angle Regression](https://web.stanford.edu/~hastie/Papers/LARS/LeastAngle_2002.pdf)
* [Support-vector networks](https://link.springer.com/article/10.1007/BF00994018)
* [Maximum Margin Interval Trees](http://papers.nips.cc/paper/7080-maximum-margin-interval-trees)
* [Direct Importance Estimation with Model Selection and Its Application to Covariate Shift Adaptation](http://papers.nips.cc/paper/3248-direct-importance-estimation-with-model-selection-and-its-application-to-covariate-shift-adaptation)
* [A survey of point-based POMDP solvers](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.711.9951&rep=rep1&type=pdf)

## Lectures on figure creation

* R data.table + animint2 http://members.cbio.mines-paristech.fr/~thocking/animint2-manual/Ch02-ggplot2.html
* R tidyverse + ggplot2 https://r4ds.had.co.nz/data-visualisation.html
* python pandas + seaborn https://towardsdatascience.com/introduction-to-data-visualization-in-python-89a54c97fbed
* julia Plots http://docs.juliaplots.org/latest/

## books

Murphy

* https://www.cs.ubc.ca/~murphyk/MLbook/
* NAU library https://arizona-nau-primo.hosted.exlibrisgroup.com/primo-explore/fulldisplay?docid=01NAU_ALMA51166833980003842&context=L&vid=01NAU&lang=en_US&search_scope=Everything&adaptor=Local%20Search%20Engine&tab=default_tab&query=any,contains,murphy%20machine%20learning&sortby=rank&mode=Basic
* e-book http://eds.a.ebscohost.com/ehost/ebookviewer/ebook?sid=f4a68ba6-099a-4015-9d63-a342771786f3%40sdc-v-sessmgr02&vid=0&format=EB

Hastie, Tibshirani, Friedman

* https://web.stanford.edu/~hastie/ElemStatLearn/

## Lectures on reproducibility

* Karl Broman's reproducible research tutorial https://kbroman.org/steps2rr/
* Karl Broman's minimal make tutorial https://kbroman.org/minimal_make/ 
* Karl Broman's knitr tutorial https://kbroman.org/knitr_knutshell/
* R markdown https://r4ds.had.co.nz/r-markdown.html

## criteria for paper presentations

### My checklist for reviewing papers

Is each of the following a strength of the paper? Otherwise, how is it a weakness?

* Theoretical results / proofs
* Empirical results / real data / convincing figures (with error bands)
* Good/clear English
* Easy to understand math / everything well defined
* Novel idea
* Very clear about what is new relative to previous work


### NeurIPS

from https://nips.cc/Conferences/2019/PaperInformation/ReviewerGuidelines

1. Contributions: Please list three things this paper contributes (e.g., theoretical, methodological, algorithmic, empirical contributions; bridging fields; or providing an important critical analysis). For each contribution, briefly state the level of significance (i.e., how much impact will this work have on researchers and practitioners in the future?). If you cannot think of three things, please explain why. Not all good papers will have three contributions.

2.  Detailed comments: Please provide a thorough review of the submission, including its originality, quality, clarity, and significance.

### ICML

from https://icml.cc/Conferences/2017/ReviewerGuidelines

The goal of the review is to give the community a better sense of the quality of the paper as a whole. You should discuss the strengths and weaknesses of each paper and address all the explicit criteria provided in the review form. Please read the review criteria and use those to guide your decisions. It is tempting to include only weaknesses in your review. However, it is important to also mention and take into account the strengths, as an informed decision needs to take both into account. It is particularly useful to include a list of arguments for and against acceptance.

All ICML papers should be good scientific papers, regardless of their specific area. We judge whether a paper is good using specific criteria; a reviewer should comment on all of these. We give specific instructions for how to fill out each section in the review form. This year, the review form contains the following sections:

(1) Summary of the Paper

As a whole, your written review should begin by summarizing the main ideas of each paper and relating these ideas to previous work at ICML and elsewhere. While this part of the review may not provide much new information to authors, it is invaluable to members of the program committee, and it demonstrates to the authors that you understand their paper. Please write your summary in your own words and avoid using phrases from the abstract or the paper itself. 

(2) Paper Clarity

In this section you should assess the clarity of the presentation and reproducibility of the results. Feel free to make suggestions to improve the manuscript.

Is the paper clearly written? Is it well-organized? Is the result section or are the proofs clear enough so that expert readers will understand them and can reproduce the results (if applicable)?

 

Excellent (Easy to follow): An exceptionally clear paper. Much of this paper would be accessible even to someone outside the field of machine learning.

Above Average: A good paper, clearly written. Accessible to most machine learning researchers.

Below Average: A decent paper, but could be written more clearly. Likely to be accessible only to those in similar areas.

Poor (Hard to follow): The paper is unclear. Even people working in similar areas of machine learning will have a difficult time understanding / reproducing this papers’ contributions.

(3) Paper Significance

In this section you should assess the importance (potential impact) of this submission and its relation to existing work. Consider checking the proceedings of recent machine learning conferences to make sure that each paper is significantly different from papers in previous proceedings.

Does the paper contribute a major breakthrough or an incremental advance?

Are other people (practitioners or researchers) likely to use these ideas or build on them? Does the paper address a difficult problem in a better way than previous research? 

Is it clear how this work differs from previous contributions and is related work adequately referenced? 

Excellent (substantial, novel contribution): This paper makes a contribution that could become widely known or adopted within the community.

Above Average: This paper makes a strong contribution that supports its publication.

Below Average: This paper makes an incremental contribution, and may be useful to only a small number of people.

Poor (minimal or no contribution): This paper makes little or no contribution. 

(4) Detailed comments.

In this section you should address the soundness of the paper. 

Are claims well-supported by theoretical analysis or experimental results? Is this a complete piece of work, or merely a position paper? Are the authors careful (and honest) about evaluating both the strengths and weaknesses of the work?

Please also provide any additional comments to the authors and explain the basis for your ratings while providing constructive feedback.

Finally, please provide a short 1-2 sentence summary of your review.
