# Friendship Recommendation System

### Overview
The Friendship Recommendation System is designed to suggest potential friends for a given user in a social network. It utilizes the Barabasi-Albert graph model for creating a synthetic social network and employs a basic recommendation algorithm based on the number of mutual friends.

### Features
- Graph Creation: Generates a synthetic social network using the Barabasi-Albert graph model.
- Recommendation Algorithm: Recommends friends based on the number of mutual friends.
- Random User Recommendation: Recommends friends for a randomly chosen user.

### Usage in Google Colab
- Open the Colab notebook: Friendship_Recommendation_System.ipynb
- Specify the values for 'NUM_USERS' and 'AVG_FRIENDS' to generate a customized social network.
- Run the code to view the recommendations for a randomly chosen user.
```python
NUM_USERS = 1000 # no. user in the network
AVG_FRIENDS = 5 # average friends per user
NUM_RECOM = 7 # desired no. recommendations
```

### Additional Information
- The recommend_friends method uses a subset of nodes to reduce computation time.
- Mutual friends are determined by the intersection of the user's friends and other users' friends.

Feel free to explore and customize the code to suit your needs!
