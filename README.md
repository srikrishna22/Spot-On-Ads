# Spot-On-Ads

The idea for this project started with a question: How do we create a meaningful ad?
My assumption is that ads attached to emotions are meaningful.
Advertisments are mostly done either enmasse or targeting to specific demographics. But if we can understand the emotional state of 
a viewer than we can advertise in that space. And what evokes more emotion than music?

I used Spotify(https://spotifycharts.com/regional) to get the top 200 streamed songs in the US.
The tracks' titles were inputs for the Genius API(https://docs.genius.com/) in order to get the lyrics and annotations(user created
interpretations of songs). 

I ran an NMF model with 5 features using tf-idf. And then PCA with 3 components in order to create a plotly visualization.
Songs clustered into 5 categories: Feel good, Loved and lost, Stages in a Relationship, Sex, Drugs & Rap and Espanol.
See the PDF for insights!

I'll continue to organize/update this repository.
