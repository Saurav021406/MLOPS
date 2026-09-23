### Module responsibilities

- `data.py` — Loads the delivery dataset and splits it into training and testing data.
- `features.py` — Calculates and describes features for individual delivery orders.
- `model.py` — Trains, evaluates, saves, and loads the machine-learning model.
- `validate.py` — Checks whether a delivery order contains valid values.
- `__init__.py` — Exposes the main functions of the delivery package.
- `train.py` — Runs the complete model-training pipeline from the command line.
- `predict.py` — Loads the saved model and predicts the delivery time for a new order.