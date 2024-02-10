# Paraphrase-detection-model-and-Label-noise-analysis

- **Google Collab Link** : https://colab.research.google.com/drive/1zuXoMMi2WG1q_AgCDiJUIxCUlavKWZ4h?usp=sharing

---
## Abstract
In this project, we analyze the impact of label noise on the performance of the paraphrase detection model. i.e. We will analyse the sensitivity to label noise (robustness) in our paraphrase detection model.

---
## Conclusion
The TF-IDF model is quite robust when measured for noise sensitivity. However, this comes in tradeoff to the accuracy, which is lower than neural network models which are great in accuracy in NLP tasks. This is because the dependence of our model on the training set is lower than the neural models which get all their weights and biases from the training dataset and overfit to the noise.

---
- **To Replicate the results using the above code or to use the model.**
1. Make a copy of the ipynb collab file to your own google drive.
2. Upload the train(msr_paraphrase_test.txt) and test dataset(msr_paraphrase_train.txt) to your own drive,  
use their paths in the code like  
train_filename = "drive/MyDrive/MSRParaphraseCorpus/msr_paraphrase_train.txt"  
test_filename = "drive/MyDrive/MSRParaphraseCorpus/msr_paraphrase_test.txt"
3. Run the code as Required.
---
