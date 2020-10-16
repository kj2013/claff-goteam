# CL-Aff Shared Task: Diplomacy (Deadline Nov 2020)

Corpus and annotations for the CL-Aff Shared Task - Diplomacy - from the National University of Singapore

A part of the AffCon Workshop @ AAAI 2021 for Affect in Collaborative Creation

We introduce the CLAff-Diplomacy dataset this year, which examines the role of affect in inter- and intra-team trust. It builds on the Diplomacy dataset (Peskov, Cheng, Elgohary, Barrow, Danescu-Niculescu-Mizil, & Boyd-Graber, 2020; Niculae, Kumar, Boyd-Graber, & Danescu-Niculescu-Mizil, 2015 ) with additional annotations, and derived outcomes related to collaboration.

**Registration Deadline Nov 4, 2020** 

# LICENSE

Our dataset is available under CC BY 4.0 license (https://creativecommons.org/licenses/by/4.0/)

## The Tasks

GIVEN: Utterances by players in an online game called Diplomacy, labeled for their rapport characteristics.

TASK 1 : Semi-supervised learning task: Predict labels for how the speaker is building a rapport, based on a small labeled and large unlabeled training data.

TASK 2: Unsupervised task: Explore the relationship between rapport and the receiver's trust labels.

## Corpus details 

**Unlabeled training set** : RELEASED! The Diplomacy dataset from (http://vene.ro/betrayal/)

**Labeled training set** : RELEASED! 10,000 sentences labeled for their rapport-related characteristics!

**Test set:** ETA Nov 20, 2020. Only released to registered participants.


## Label descriptions

Check out the annotation instructions under /docs/.



## Git Contents

This is the open repository for Affect Understanding in Text and Annotations contributed to the public through the collaboration between the National University of Singapore and Adobe Research India.


    ./README.md :
 
This file.


    ./FAQ2021 :
	
To be added, will have frequently asked questions including updates to the corpus.


    ./docs/annotation_instructions.html :
  
Annotation instructions for each of the labels

  

    ./docs/annotation_task.html :
  
The actual AMT task


    ./data/unlabeled data :
  
Directory containing unlabeled data pertaining to the training and the test sets.


    ./data/training data
  
To be added, directory containing the training set.


    ./data/test data

To be added, directory containing the test set.



## Organisers' Contacts

The system outputs from the test set should be submitted to the task organizers, for the collation of the final results to be presented at the workshop.

If you have any questions regarding the workshop scope or need further information, please do not hesitate to send an e-mail: 

Niyati, nchhaya [AT] adobe.com

Kokil, jaidka [AT] nus.edu.sg







## Check out the FAQ! 

Please "WATCH" this repository! We may be pushing more updates in the following weeks.
After the Shared Task, we also plan to further enrich this data, with more annotations, meta-features and trained classifiers to aid with downstream applications.

If you use the data and publish, please let us know and cite the original Diplomacy dataset papers, as well as the CL-Aff overview paper (TBA):


Niculae, V., Kumar, S., Boyd-Graber, J., & Danescu-Niculescu-Mizil, C. (2015, July). Linguistic Harbingers of Betrayal: A Case Study on an Online Strategy Game. In Proceedings of the 53rd Annual Meeting of the Association for Computational Linguistics and the 7th International Joint Conference on Natural Language Processing (Volume 1: Long Papers) (pp. 1650-1659).

Peskov, D., Cheng, B., Elgohary, A., Barrow, J., Danescu-Niculescu-Mizil, C., & Boyd-Graber, J. (2020). It Takes Two to Lie: One to Lie, and One to Listen. In Proceedings of the 57th Annual Meeting of the Association for Computational Linguistics.

## Acknowledgement

We're grateful to Cristian Danescu-Niculescu-Mizil for the original data behind this task. Thank you!


## Organizers

Kokil Jaidka, National University of Singapore

Lynnette Ng, Carnegie Mellon University

Niyati Chhaya, Big Data Experience Lab, Adobe Research

Check out the Workshop and Shared Task website: <a>https://sites.google.com/view/affcon2021/home</a>



