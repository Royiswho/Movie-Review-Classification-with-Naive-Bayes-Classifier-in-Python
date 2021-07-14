# Movie Review Classification with Naive Bayes Classifier in Python
 
### author: Yi Rong

### date: 07/14/21
---

#### 1. Build a	Naive Bayes Classifier to classify reviews based on	these five reviews below:

Review 1: "innovative action movie sequences" - I don't know, it all seem like crap from a Power Rangers episode.

Review	2:	And what is wrong with focusing on the messages of a film?

Review	3:	I hated the movie and I really wanted to like it.

Review	4:	Amazing actually.

Review	5:	Honestly, I still found it to be the best of the current wave of live action Disney movie remakes.

#### 2. Test the algorithm to classify following messages.

Test	1:	I	think	amazing	action	movie.

prediction: class 1, positive

Test	2:	I	really	liked	it.

prediction: class 0, negative

Comment: Based on the trained Naive Bayes Classifier, test 1 (review 6) is a positive reivew (class 1) and test 2 (review 7) is a negative review, although test 2 looks like a positive review. Its words, "really" and "like", only appear in the negative reviews. So, this problem can be solved by increasing inputs and decrasing the coincidence.