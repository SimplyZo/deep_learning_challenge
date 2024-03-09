## Optimizing Neural Network for Charity Funding Prediction
Overview
In this project, I aimed to develop and optimize a neural network model to predict the success of charity funding applications. My goal was to achieve at least 75% accuracy in these predictions. Despite my efforts and three major attempts to refine and improve our model, I fell slightly short of this target. Below is the summary and approaches taken, adjustments made, and the results.

Initial Setup
I started by preparing my dataset, which involved:

Importing necessary libraries (e.g., TensorFlow, scikit-learn, pandas).
Reading and preprocessing the data, including dropping non-beneficial ID columns and converting categorical data to numeric using pd.get_dummies.
Splitting the data into feature and target arrays, then into training and testing sets.
Scaling the feature data to normalize its range.
Model Development and Attempts

First Attempt
My initial model consisted of a simple neural network with two hidden layers. Despite this being a good starting point, the model's performance did not meet the 75 % accuracy mark. The accuracy was around 72.5%, which prompted to look for ways to enhance the model.

Adjustments Made
To try and improve our model's accuracy, I employed several strategies across our following attempts, including:

Increasing Model Complexity: I added more neurons and layers to capture more complex patterns in the data.
Regularization Techniques: dropout layers were added to prevent overfitting and improve the model's generalization ability.
Optimization Adjustments: Adjustments were made to the learning rate and optimizer settings in hopes of finding a better fit for our data.
Early Stopping: We implemented early stopping to halt training when the validation loss ceased to improve, preventing overfitting.

Second and Third Attempts
With each attempt, I fine-tuned the model by adjusting the architecture, number of neurons, layers, and incorporating regularization techniques like dropout. I experimented with different batch sizes and epochs to optimize the training process.

Results
First Attempt: Provided a baseline performance.
Second Attempt: Showed improvement by adjusting the network architecture and regularization, reaching an accuracy of approximately 72.54%.
Third Attempt: Despite further optimizations and employing techniques such as early stopping, the accuracy slightly improved but still did not reach the 75% threshold.

Conclusion
Throughout this project, I learned a great deal about neural network optimization and the challenges of achieving high accuracy on specific tasks. Although I did not reach our target accuracy, the iterative process of refining the model provided valuable insights into neural network tuning and the importance of data preprocessing.