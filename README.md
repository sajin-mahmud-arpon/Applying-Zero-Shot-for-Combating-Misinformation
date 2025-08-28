# Applying-Zero-Shot-for-Combating-Misinformation
Abstract—The number of fake contents being spread on the
 internet platforms in rapid succession has led to the importance
 of the detection of fake news. One practical step is zero
shot classification with pre-trained language models that do
 not need further fine-tuning. In this paper, four transformer
 models DeBERTa, BART, ModernBERT, and CE-DeBERTa are
 evaluated on a smaller variant of the Kaggle Fake News dataset
 licensed under CC BY-4.0. Majority Voting and Soft Voting (with
 0.85 and 0.92 threshold) are also being used as ensemble learning
 method to enhance reliability. The top-accuracy (76.91%), and
 F1-score (72.64%), and the greatest degree of uncertainty (59.40)
 were found in DeBERTa. However, ModernBERT showed less
 performance (F1-score: 62.40%) with the lowest uncertainty
 (31.09%). DeBERTa achieved the highest score of 0.6939 based on
 the composite performance score. The highest accuracy (70.23%)
 and the highest uncertainty (31.99%) were obtained with Soft
 Voting with a threshold of 0.92 among ensemble methods.
 But Majority Voting turned out to have the strongest overall
 performance score (0.7089). In general, DeBERTa and Majority
 Voting ensemble are rather successful in terms of trustworthy
 fake news identification.
