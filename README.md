# Creating Music Playlists with Unsupervised Learning

I have never been one to create music playlsits on Spotify. Most often, I don't want to take the time to create playlists and on the rare occasions I do attempt to make a playlist, I can't decide how I should structure my playlists. Therefore, any song I like ends up in the 'Liked Songs' list with the rest of my 500+ saved songs. I was interested in exploring unsupervised learning methods as a possible solution. 

### Objective: Use a K-means clustering algorithm to separate my songs into playlists. The goal is create playlists that appear to be logical in terms of song similarity. Use the Spotify API to create Spotify playlists in Python.

#### 1. Obtain saved songs with the Spotify API
#### 2. EDA
#### 3. K-Means clustering
#### 4. Create playlists with the Spotify API


<br>You can find the main steps of the K-Means clustering process below.<br>

The Elbow method was used to select the optimal number of clusters. (Select k where the Within-Cluster-Sum of Squared Errors starts to diminish, or where the curve begins to level out.) A k value of 5 was chosen for this application. 

<br><img width="650" alt="Screen Shot 2020-11-03 at 7 20 58 PM" src="https://user-images.githubusercontent.com/54564733/98058216-bed37480-1e09-11eb-9c70-5a03065a44fa.png"><br><br>

#### The number of songs in each cluster
<br><img width="513" alt="Screen Shot 2020-11-08 at 12 50 04 PM" src="https://user-images.githubusercontent.com/54564733/98481599-eedf9680-21c0-11eb-8d4d-606cc7ee545b.png"><br><br>

#### Visualization the Clusters with a Principle Component Analysis: 
<br><img width="735" alt="Screen Shot 2020-11-08 at 12 49 11 PM" src="https://user-images.githubusercontent.com/54564733/98481580-cf486e00-21c0-11eb-808f-fa458d1c71f7.png"><br><br>

#### PCA with 3 components
<br><img width="950" alt="Screen Shot 2020-11-08 at 12 49 36 PM" src="https://user-images.githubusercontent.com/54564733/98481592-dec7b700-21c0-11eb-9098-830420e8d99e.png"><br><br>

#### Comparing the mean values of some features accross clusters
<br><img width="570" alt="Screen Shot 2020-11-03 at 7 42 52 PM" src="https://user-images.githubusercontent.com/54564733/98059502-e8da6600-1e0c-11eb-8e2c-30d8ff972c15.png"><br><br>

### Creating a playlist for each cluster using the Spotify API.
<br><img width="1130" alt="Screen Shot 2020-11-08 at 12 47 49 PM" src="https://user-images.githubusercontent.com/54564733/98481567-bdff6180-21c0-11eb-8ad9-6750190c61e9.png"><br><br>




