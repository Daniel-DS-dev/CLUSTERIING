# Unsupervised Learning (CLUSTERING)
## NOTE: Read this first, it will only take about 5-7 minutes.
* This a notebook explaining in simple terms, how to use unsupervised machine learning algorithms, specifically; Flat Clustering (K-Means Clustering) and Hierachical Clustering (Mean-Shift)

### Firstly Let's define what machine learning is
## Machine Learning is simply the ability of a machine to predict outcomes, analyze patterns, and give recommendation, without being explicitly programmed.
### Types of Machine Learning:
## Supervised Learning: 
 * Here we have labelled data, and we know the target before we run our models, so we can measure the inaccuracy of the model through the objective function and improve results through optimization algorithm. What we supervise is the training itself. Types of supervised learning include: Support Vector Machines (SVM), Neural Networks, deep learning, Random forests, Bayesian networks

## Unsupervised Machine Learning:
* Unsupervised learning is a machine learning technique in which users do not need to supervise the model, all you have to do is give the model unlabeled data containing different features and the model will discover new patterns and information contained in the data.

* Let me give you an example of unsupervised learning:
* It's your first invasion, you are an alien. You are invading planet Earth, this planet is inhabited by some primitive life form called humans, and you have never seen a human before.
Your alien spaceship takes off at 8:00am in the morning from planet Amala, and by 8:02am your spaceship is already hovering over earth because, you know spaceships travel at light speed (basically they travel really fast). 
Now on planet Earth, you land in a place called Lagos, Nigeria.
You immediately notice that Lagos is densely populated with humans, so dense it was unhealthy by your alien standards. 
You see your first human, very primitive looking creature. It had short hair, it was producing deep sounds, facial hair, narrow waists and it had broad shoulders. You see many humans like that.
You see another set of humans, these ones have long hair, produced thin sounds, slimmer shoulders, broad waists and little facial hair. You see many like that also.

After spending about 1 week in Lagos, Nigeria, Earth, and seeing about 2 million humans, you came to a conclusion that there were two classes of humans based on their physical appearance/features:
 * Class A: Short hair, Deep voice, A lot of facial hair, Narrow waists and Broad shoulders
 * Class B: Long hair, Thin voice, Small facial hair, Broad waists and Narrow shoulders
 
 
This is simply what unsupervised learning is about, you had never seen humans before until today, but after seeing millions of them you were able to classify humans into two distinct classes above (Class A and Class B). You later learnt that the humans in Class A are called "Male", while humans in Class B are called Female.

The most popular type of Unsupervised Machine Learning is called Clustering.

### Clustering:
  Clustering is an important concept when it comes to unsupervised learning. It mainly deals with finding a structure or pattern in a collection of unlabeled data. Clustering algorithms will process your data and find natural clusters(groups) if they exist in the data. You can also modify how many clusters your algorithms should identify. It allows you to adjust the granularity of these groups.
  
Two most common forms of clustering:
1. Flat Clustering (K-Means Clustering)
2. Hierarchical Clustering (Mean-Shift)

#### Check the notebooks in this repository for the explanations and examples of these 2 forms of clustering. This repository also includes a notebook showing the application of hierarchical clustering to the common titanic dataset.


### Major differences between Unsupervised learning and Supervised learning:
 * Supervised deals with labeled data while unsupervised doesn't
 * Supervised learning is a highly accurate and trustworthy method while unsupervised isn't
 * Supervised is a a simpler method while Unsupervised is computationally complex.
 
I know, I know.... It seems Unsupervised learning is not great compared to Supervised machine Learning. It is true right now it is, but maybe with more research and all of that this will change in future. Eventhough unsupervised is not as widely used as supervised, it has it's own applications too:
 * Clustering automatically split the dataset into groups base on their similarities
 * Anomaly detection can discover unusual data points in your dataset. It is useful for finding fraudulent transactions
 * Association mining identifies sets of items which often occur together in your dataset
 * Latent variable models are widely used for data preprocessing. Like reducing the number of features in a dataset or decomposing the dataset into multiple components

You can read more on Machine learning and it's types online.

