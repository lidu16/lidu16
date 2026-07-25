# Hi — I'm Lidiya Mesenbet 👋

[![Email](https://img.shields.io/badge/Email-lidiyamesenbet16%40gmail.com-c14438?logo=gmail)](mailto:lidiyamesenbet16@gmail.com) [![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-0A66C2?logo=linkedin)](https://www.linkedin.com/feed/update/urn:li:activity:7461368486683058176/) [![Twitter](https://img.shields.io/badge/Twitter-@lidu16-1DA1F2?logo=twitter)](https://twitter.com/lidu16)

## Overview
I’m a developer focused on Machine Learning and Artificial Intelligence. I prototype models, evaluate performance, and deploy them as APIs so they can be integrated into products and workflows. My work emphasizes practical, data-driven solutions that deliver measurable value.

## Projects (selected ML work)
- 0bject-detection — object detection experiments and model training: https://github.com/lidu16/0bject-detection
- fraud-detection — Jupyter notebooks for fraud detection workflows: https://github.com/lidu16/fraud-detection
- credit-risk-model — credit scoring model experiments: https://github.com/lidu16/credit-risk-model
- news-sentiment-project — linking news sentiment to market movements: https://github.com/lidu16/news-sentiment-project
- brent-oil-change-point-analysis — time-series change point analysis: https://github.com/lidu16/brent-oil-change-point-analysis
- letsStartAI — introductory AI projects and experiments: https://github.com/lidu16/letsStartAI

(See my repositories for more notebooks and analyses: https://github.com/lidu16)

## Short examples
A minimal scikit-learn pipeline for a classification task:

```python
from sklearn.pipeline import Pipeline
from sklearn.impute import SimpleImputer
from sklearn.preprocessing import StandardScaler
from sklearn.ensemble import RandomForestClassifier

pipeline = Pipeline([
    ("imputer", SimpleImputer(strategy="median")),
    ("scaler", StandardScaler()),
    ("clf", RandomForestClassifier(n_estimators=100, random_state=0))
])

pipeline.fit(X_train, y_train)
preds = pipeline.predict(X_test)
```

A concise PyTorch training loop skeleton:

```python
import torch
from torch import nn, optim

model = nn.Sequential(nn.Linear(128, 64), nn.ReLU(), nn.Linear(64, 10))
optimizer = optim.Adam(model.parameters(), lr=1e-3)
loss_fn = nn.CrossEntropyLoss()

for epoch in range(10):
    model.train()
    for xb, yb in train_loader:
        preds = model(xb)
        loss = loss_fn(preds, yb)
        optimizer.zero_grad()
        loss.backward()
        optimizer.step()
```

## Contact
- Email: lidiyamesenbet16@gmail.com
- LinkedIn: https://www.linkedin.com/feed/update/urn:li:activity:7461368486683058176/
- Twitter: https://twitter.com/lidu16

If you'd like me to shorten further, change tone to more casual or more formal, or add screenshots and project highlights, tell me which tone and which projects to feature and I’ll update it.