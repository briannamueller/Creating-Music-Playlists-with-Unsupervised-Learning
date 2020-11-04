# Creating Music Playlists with Unsupervised Learning

I have never been one to create music playlsits on Spotify. Most oftten, I don't want to take the time to create playlists On the rare occasions I do attempt to make a playlist, I don't know what's the best way to group my songs. Therefore, any song I like ends up in the 'Liked Songs' list with the rest of my 500+ saved songs. I wanted to see if I could use unsupervised learning as a solution. 

### Objective: Use the K-means clustering algorithm to separate my songs into playlists. The goal is create playlists that 'make sense' in terms of song similarity.

#### 1. Data cleaning / transformation
#### 2. EDA
#### 3. K-Means clustering

<br>You can find main steps of the K-Means clustering process below.<br>

The Elbow method was used to select the optimal number of clusters. (Select k where the Within-Cluster-Sum of Squared Errors starts to diminish, or where the curve begins to level out.) A k value of 5 was chosen for this application. 

<br><img width="650" alt="Screen Shot 2020-11-03 at 7 20 58 PM" src="https://user-images.githubusercontent.com/54564733/98058216-bed37480-1e09-11eb-9c70-5a03065a44fa.png"><br><br>

The number of songs in each cluster
<br><img width="477" alt="Screen Shot 2020-11-03 at 7 27 45 PM" src="https://user-images.githubusercontent.com/54564733/98058567-b3347d80-1e0a-11eb-9cd1-45490d243527.png"><br><br>

Visualization the Clusters with a Principle Component Analysis: 
<br><img width="740" alt="Screen Shot 2020-11-03 at 7 30 30 PM" src="https://user-images.githubusercontent.com/54564733/98059117-f8a57a80-1e0b-11eb-91aa-09f559e6423d.png"><br><br>

PCA with 3 components



