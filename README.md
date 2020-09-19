# SemEval-2012 Task 6: Semantic Textual Similarity
*Project done for the IHLT (Introduction to Human Language Technology) course (Master in Artificial Intelligence at UPC)*

Authors:
- Albert Rial
- Utku Ünal

This repository contains two different approaches to address the SemEval 2012 Task 6 (Semantic Textual Similarity) which consists in, given two pair of sentences, provide a similarity value between them. This task is also known as paraphrases detection. A paraphrase between two sentences or texts is when both have the same meaning using different words. 

In the repository you can find the following files and folders:
- sts-model.ipynb: jupyter notebook containing our first approach together with the explanations and results obtained.

- sts-model-infersent.ipynb: another jupyter notebook where we have another approach that uses a pre-trained sentence embeddings model (InferSent).

- sts-summary.pdf: PDF file containing a brief presentation about the work done, the approaches taken and all the results obtained.

- train/test-gold: datasets of the STS competition provided in the subject and used for training and testing.

**Important**: In order to run the InferSent approach, it is needed the InferSent library, the fastText word embeddings dataset and a pre-trained model of InferSent.

## Results
The best result obtained is (pearson correlation between the gold-standard similarity values and the ones from our system): **82.46%**.
This result overpasses the result obtained by the winner of the SemEval 2012 competition.

