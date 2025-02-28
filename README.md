# Quora-Question-Pair-analysis

The goal of this Notebook is to predict which of the provided pairs of questions contain two questions with the same meaning. The ground truth is the set of labels that have been supplied by human experts. The ground truth labels are inherently subjective, as the true meaning of sentences can never be known with certainty. Human labeling is also a 'noisy' process, and reasonable people will disagree. As a result, the ground truth labels on this dataset should be taken to be 'informed' but not 100% accurate, and may include incorrect labeling. It is believed the labels, on the whole, to represent a reasonable consensus, but this may often not be true on a case by case basis for individual items in the dataset.

</br>

## Data-Fields

 id - the id of a training set question pair </br>
 qid1, qid2 - unique ids of each question (only available in train.csv) </br>
 question1, question2 - the full text of each question </br>
 is_duplicate - the target variable, set to 1 if question1 and question2 have essentially the same meaning, and 0 otherwise.
 
 
