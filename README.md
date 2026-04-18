# 100-Days-of-Machine-Learning
Documenting my daily progress and learning in machine learning, one day at a time!

Day 1: Introduction to Machine Learning

- Learned ML finds patterns from data.
- Unlike traditional coding, we don’t write explicit rules.
- We feed input-output pairs, and the system learns patterns.
- Also discovered data mining, which extracts hidden patterns from large data.
Excited for tomorrow!


Day 2: Types of Machine Learning (Based on Supervision)
- Supervised:
  - Regression: Target is numerical.
  - Classification: Target is categorical.
- Unsupervised:
  - No target variable. Algorithms learn patterns like clustering, dimensionality reduction, anomaly detection.
- Semi-supervised:
  - Combination of both labeled and unlabeled data.
- Reinforcement:
  - An agent learns by interacting with an environment.
 

Day 3: Batch vs. Online Machine Learning & Instance vs. Model-based Learning

- Batch vs. Online Machine Learning:
  - Batch Learning: We train the model offline using a large dataset. It takes time. After training, we deploy it. When new data comes in, we have to pull the model back, retrain offline again, and redeploy.
  - Online Learning: The model updates in real-time with small data increments. The model keeps refining. But we need to be careful: bad data can sneak in, so constant monitoring is key.
   
- Instance vs. Model-based Learning:
  - Instance-based: The model looks at the data when queried, using similarities or neighbors to make predictions without forming a general pattern beforehand.
  - Model-based: We train a model to learn a pattern or rule from data. Once trained, it uses that pattern to predict future inputs.
