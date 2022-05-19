# Youtube-Spam-Detection
## Abstract 
Google’s new video distribution network YouTube
has drawn a rising number of customers due to its profitability.
However, such popularity has attracted nefarious people who
want to market themselves or spread viruses and malware.
Because YouTube only provides limited comment moderating
tools, the level of spam is shockingly increasing, leading several
well-known channels to block the comments section of their
videos. Because the posts are short and often replete with slangs,
symbols, and acronyms, automatic comment spam filtering on
YouTube is a difficulty even for proven categorization systems.
We evaluated several high-performance classification techniques
for this purpose in this study.• YouTube API : https://github.com/ThioJoe/YT-SpammerPurge/wiki/Instructions:-Obtaining-an-API-Key
• YouTube API Video Comment
## Methodology
A) Data Sources -
• YouTube API : https://github.com/ThioJoe/YT-SpammerPurge/wiki/Instructions:-Obtaining-an-API-Key
• YouTube API Video Comment
• http://mlg.ucd.ie/yt/

B) Data Description -
Data was scraped from YouTube, and it was possible to
retrieve comments for a certain video id using the YouTube
data. The original content, author name, number of likes, and
total number of comments were all retrieved. Two annotated
data sets were used in addition to the scraped data.Our data
set consists of 6433427 comments, of which 0.925 are not
spam(ham) and the rest 0.075 are spam.

C) Models - 
i) Random Forest Classifier - Random Forest
consists of a large number of individual decision trees that
operate on ensemble. Each individual tree in the random
forest spits out a class prediction and the class with the most
votes becomes our model’s prediction. It uses bagging and
feature randomness when building each individual tree to try
to uncorrelated forest of trees whose prediction by committee
is more accurate than that of any individual tree

ii) Decision Tree - A decision tree or a classification
tree is a tree in which each internal (non-leaf) node is labeled
with an input feature. The arcs coming from a node labeled
with an input feature are labeled with each of the possible
values of the target feature or the arc leads to a subordinate
decision node on a different input feature. Each leaf of the tree
is labeled with a class or a probability distribution over the
classes, signifying that the data set has been classified by the
tree into either a specific class, or into a particular probability
distribution (which, if the decision tree is well-constructed, is
skewed towards certain subsets of classes).They are are a non-parametric supervised learning method used for classification
and regression.The goal is to create a model that predicts the
value of a target variable based on several input variables.

iii) Multinomial Naive Bayes: The Bayes theorem
is the foundation of Naive Bayes, which states that features in
a dataset are mutually independent. The occurrence of one trait
has no bearing on the likelihood of the occurrence of the other.
Naive Bayes predicts a text’s tag. They calculate each tag’s
probability for a given text and output the tag with the highest
probability. For Example, Spam filtering in email, Diagnosis
of diseases, making decisions about treatment, Classification
of RNA sequences in taxonomic studies where, PA= the prior probability of occurring A PBA=
the condition probability of B given that A occurs PAB=
the condition probability of A given that B occurs PB= the probability of occurring B In this project, our goal is to filter
spam YouTube comments so Multinomial Na¨ıve Bayes can
be one of the models used to perform the analysis. The most
significant sub-tasks in text classification are feature extraction
and selection. The following are the three main criteria for
good features: Salient: The features should be meaningful and
important to the problem Invariant: The features are resistant
to scaling, distortion, and orientation etc. Discriminatory:
For training of classifiers, the features should have enough
information to distinguish between text.

iv) STOCHASTIC GRADIENT DESCENT - Classifier
(Support Vector Classification): The Stochastic Gradient Descent - Classifier (SGD-Classifier) is an SGD-optimized linear
classifier (SVM, logistic regression). SVMs are a class of
supervised learning methods for classification, regression, and
outlier detection. High-dimensional spaces are where support
vector machines shine. Cases in which the number of dimensions exceeds the number of samples. It is memory efficient
because it uses a subset of training points (called support
vectors) in the decision function.

## Conclusion
The purpose of the study was to discover effective methods and settings for detecting spam comments on YouTube.
Various strategies are used to categorize YouTube comments
as spam and not spam (ham). This method was tested with
real-time YouTube comments and yielded an overall accuracy
of 0.95. Because the YouTube API is an open platform for all
users, it may influence spammers’ behaviour over time. In the
actual world, the YouTube spam feature will not be steady; it
will change rapidly.

