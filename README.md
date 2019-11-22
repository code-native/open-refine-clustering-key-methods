# OpenRefine Clustering Key Methods

## Motivation

[OpenRefine](http://openrefine.org/) has effetive text clustering feature. It is based on several text signature methodologies.  

1. Fingerprint
2. N-Gram Fingerprint
3. Phonetic Fingerprint
4. Nearest Neighbor Methods
5. Levenshtein Distance
6. PPM

I want to create a easy to use API based on these methods. Implementation is in Python. Live API is serverless.

## Prior Art

### OpenRefine

If you want to have a quick overview on how OpenRefine clustern works watch this [Video: 4 minutes](https://www.youtube.com/watch?v=-aa02-9lf8o). OpenRefine has detailed explaination of the clustering feature and description of all methods in their [Clustering In Depth wiki](https://github.com/OpenRefine/OpenRefine/wiki/Clustering-In-Depth).

### Python Packages

I want to reduce the amount code I write and maintain. There are already many fine implementation of the algorithems we want. Each package is evaluated to determind its suitablility.

1. Fingerprint
2. N-Gram Fingerprint
- [ngram](https://pypi.org/project/ngram/3.2/)

3. Phonetic Fingerprint
- [abydos](https://pypi.org/project/abydos/)

4. Nearest Neighbor Methods (kNN)
- [Scikit-Learn](https://scikit-learn.org/)

5. Levenshtein Distance
- [abydos](https://pypi.org/project/abydos/)
- [python-Levenshtein](https://pypi.org/project/python-Levenshtein/)

6. Prediction by Partial Matching

