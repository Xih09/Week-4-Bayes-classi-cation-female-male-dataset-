Download link :

Exercise – Week 4: Bayes classi cation (female-male dataset)
Be prepared for the exercise sessions (watch the demo lecture). You may ask TAs to help if you cannot make your program to work, but don’t expect them to show you how to start from the scratch.

    Male and female { Bayesian classi er (40 points) Download the male and female height and weight measurements:

        male female X train.txt

        male female X test.txt

        male female y train.txt

        male female y test.txt

    Height and weight histograms (10 points)

Compute the histograms of the male height, female height, male weight and female height measure-ments using the NumPy histogram() function. For the both use 10 bins and xed ranges ([80; 220] for height and [30; 180] for weight).

Plot two histograms, one for height and another for weight, that includes the both classes. Estimate visually which measurement is likely better for classi cation.

Return the following items:

        Python code: <surname> male female histogram.py

        A full desktop screenshot that includes a terminal window executing your code: <surname> male female histogram desktop.png

        The histogram plot 1: <surname> male female histogram plot height.png

        The histogram plot 2: <surname> male female histogram plot weight.png

    Baseline classi er (10 points)

Make a classi er that assigns a random class to each test sample and computes its classi cation accuracy. Print the accuracy.

Make another classi er that assigns the most likely class (highest a priori) to all test samples. Print the accuracy.

Return the following items:

        Python code (single le): <surname> male female baseline.py

        A full desktop screenshot that includes a terminal window executing your code: <surname> male female baseline desktop.png

    Bayes classi er with non-parametric distribution (20 points) Compute and print the prior probabilities for male and female.

Compute class likelihoods, p(heightjmale), p(weightjmale), p(heightjfemale) and p(weightjfemale) for all test samples. This can be done by using the bin min/max values returned by NumPy histogram() function. You can calculate the centroid of each bin and assign each test sample to the closest bin. After knowing the bin index, the likelihood can be computed using the count vector provided by the same histogram() function.

Classify all test samples and compute the classi cation accuracy. Print accuracies for height only, weight only, and weight and height together (multiply likelihoods).

Return the following items:

        Python code (single le): <surname> male female bayes.py

        A full desktop screenshot that includes a terminal window executing your code: <surname> male female bayes desktop.png

1
