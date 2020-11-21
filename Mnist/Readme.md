Digit recognizer using famous mnist dataset. In the project I compare three different models,
namely: KNN, KNN with locality-sensitive hashing and Convolutional Neural Nets, in case of speed and accuracy.
Conclusions:
Classifier based on convolutional neural network was the best in case of accuracy (99.13%) leaving behind two other classifiers. Hovewer it's training takes quite a long time (about 10 minutes). Next classifier, one using KNN, had accuracy of about 97% with a runtime of nearly 90s. The last classifier (KNN with LSH) was trying to optimize KNN in case of it's runtime. It was nearly 9 times faster than KNN (runtime-10s) having not that bad accuracy of 95.5%.
