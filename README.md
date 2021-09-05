# FakeNewsClassifier

Fake News Classification with **MultinomialNB** and **Passive Aggressive Classifier Algorithm**.  
Observing the effect of hyperparameter **alpha** in MultinomialNB.  
For the purpose of simplicity training data only includes **"text"** column.


## Sample of Dataset
| id     | title | author | text | label|
| ------ | ----- | ------ | ---- | ---- |
0        | House Dem Aide: We Didn’t Even See Comey’s Let... | Darrell Lucus	 | House Dem Aide: We Didn’t Even See Comey’s Let...	 | 1|
1        | FLYNN: Hillary Clinton, Big Woman on Campus - ... | Daniel J. Flynn | Ever get the feeling your life circles the rou...   | 0|  

More information about dataset is accessable in https://www.kaggle.com/c/fake-news/data#

## Result
MultinomialNB(default) _Accuracy : 0.904_    
Passive Aggressive Classifier _Accuracy : 0.915_   

_Each Algorithms' confusion matrices and effect of hyperparameter can be viewed in colab notebook._ 


## Acknowledgements
https://www.kaggle.com/c/fake-news/data#
