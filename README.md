### Data Scaling Process

I liked how we used the scaling. Tonight (03/31/24) I learned about how improper scaling can cause data leakage.

I now understand that we need to 

1. Split the data first: This way, the model gets to play with some fresh, unseen data during testing.

2. Scaling the Training Data only: This ensures that the model learns from properly scaled features without glimpsing at the test set. 

3. Applying the Scale to Testing Data: Use the same scale parameters on the testing data. 

### Folder organization
I deleted the checkpoint folder to make things tidy. 

### Variable name deviations
Just to note, you'll find predictions for logistic regression under `lr_predictions` and for random forest under `rf_predictions`.

### Assistance

GitHub Copilot helped me a bunch. 
