# SNA-Product-Recommendation

This project aims to predict the next item that a user will click on in a browsing session. We leverage three types of data for this prediction:

1. **User Click History**: A list of products that the user has previously clicked on in the session.
2. **Graph of Historical Clicking Habits**: A graph generated from historical clicking habits from other users.
3. **Product Information**: Information about each product in the dataset, including title, price, brand, color, size, and description.

The data used in this project is sourced from the [Amazon KDD Cup'23](https://www.aicrowd.com/challenges/amazon-kdd-cup-23-multilingual-recommendation-challenge/problems/task-1-next-product-recommendation/dataset_files), with a focus on United Kingdom sessions and products.

## Model Architecture

To learn from this data, we employ a graph neural network with the following architecture:
- Three convolutional layers
- One fully connected layer

## Results

The results from our model demonstrate a significant improvement over random predictions, indicating that it has learned valuable insights from the training data. These findings suggest that the model could be utilized effectively to recommend products to users given sufficient time and data.
