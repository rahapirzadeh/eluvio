# Eluvio: Machine Learning/Data Science Test

For this data set, I wanted to answer a couple of questions and get some data from the dataset. 

I first started looking at the variables I was working with, and two stood out, the first being authors. I started by creating a simple bar plot to view the top 20 posted authors, which we could use the data later on. The following variable I wanted to look into was the date created. I started by cleaning the order to view month and year separately. I created subplots, but ultimately made a heat map to view all the data, which was very interesting to see. 

After these preliminary results, I went further in looking at the other variables. An interesting question that came to be was whether the title of the post reflects the number of upvotes you receive. And after training and testing on the dataset and plotting the findings, we see that there isn't a direct correlation between the votes and title. 

However, more can still be done with the title of the posts and the upvotes. By first viewing the top 10 posts with the number of upvotes, I created a plot that includes the mean number of posts with their upvotes over the date created. 

And finally, I decided to focus on natural language processing, and by using word2vec, I wanted to analyze the titles and predict the post's success. Using a pre-trained model, I separated all the words from the titles and got rid of the filler words (a, the, in, by, etc.). By passing the list of titles to the pre-trained list, the titles received a score that clusters could plot. The scatter plot confirmed that similar words cluster together. Now that it worked on words, I wanted to see if it would do the same with titles and if any pattern would emerge and they did. 

A potential new project would be to get the list of posts from the top 10 or so authors and see if the authors tend to write similar posts. 
