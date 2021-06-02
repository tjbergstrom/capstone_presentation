## Senior Capstone Project
### University of Alaska Anchorage, Spring 2021
### Ty Bergstrom

<br>

### I developed an app for the Alaska Public Health Information Response Team to help monitor and respond to health misinformation in social media. The app significantly simplifies their notification process. I also used the app as an opportunity to provide a variety of Machine Learning and Natural Language Processing tools and data visuals to help their efforts. This is a brief overview of some of the cool features.

You can read more about the team [here](https://www.uaa.alaska.edu/news/archive/2021/04/students-faculty-curb-misinformation.cshtml?utm_source=seawolfweekly&utm_medium=email&utm_content=SW_20210421&utm_campaign=Green+and+Gold+News).

<br>

## The App

<br>

![alt text](https://raw.githubusercontent.com/tjbergstrom/capstone_presentation/main/assets/00a.png)

The students who monitor social media pages for misinformation can easily log in and submit the link to a comment along with the text. Optional notes aid communication between monitors and responders.

<br>

![alt text](https://raw.githubusercontent.com/tjbergstrom/capstone_presentation/main/assets/00b.png)

The misinformation classifier checks that the comment really is misinformation. If it is, then the response team receives an automatic email with a link to the comment.

<br>

![alt text](https://raw.githubusercontent.com/tjbergstrom/capstone_presentation/main/assets/LSTM.png)

I developed the misinformation classifier with a Long Short Term Memory (LSTM) neural network using custom datasets of thousands of comments that I collected. The classifier replaces manual filtering by a professor, which was a bottleneck in their previous messaging system. This new system also helps save time by checking for duplicates and other filtering checks.

<br>

![alt text](https://raw.githubusercontent.com/tjbergstrom/capstone_presentation/main/assets/01a.png)

The Response Team members can also log in and quickly view the newest comments, along with the links.

<br>

## The ML and NLP projects

<br>

![alt text](https://raw.githubusercontent.com/tjbergstrom/capstone_presentation/main/assets/03a.png)

I also took the unique opportunity to work more with the data. The app is also an interface for generating data visualizations with different ML and NLP tools. The data is based on all of the misinformation comments submitted to the app.

<br>

### Most frequent words

<br>

![alt text](https://raw.githubusercontent.com/tjbergstrom/capstone_presentation/main/assets/04a.png)

It's easy to generate the data visuals over a selected time range. It's very informative to compare different visuals over different time ranges.

<br>

![alt text](https://raw.githubusercontent.com/tjbergstrom/capstone_presentation/main/assets/04b.png)

WordClouds are a nice way of visualizing the most frequent and important words in a text. This one is an example of processing the text data to get the bigrams, or combinations of two words, which adds more information in contrast to only single words.

<br>

![alt text](https://raw.githubusercontent.com/tjbergstrom/capstone_presentation/main/assets/05a.png)

![alt text](https://raw.githubusercontent.com/tjbergstrom/capstone_presentation/main/assets/05b.png)

Another way of visualizing frequent words in misinformation comments is just with a bar plot.

<br>

### Topic modelling

<br>

![alt text](https://raw.githubusercontent.com/tjbergstrom/capstone_presentation/main/assets/06a.png)

Topic modelling is a great NLP project. It's an unsupervised machine learning technique that attempts to cluster text samples into groups based on similar characteristics. I used Latent Dirichlet Allocation (LDA).

<br>

![alt text](https://raw.githubusercontent.com/tjbergstrom/capstone_presentation/main/assets/06b.png)

The topic WordClouds are clusters of the words most strongly associated with each topic. It takes some practice to analyze the results, and it's a great way to help track the trending topics in misinformation comments.

<br>

### Sentiment analysis

<br>

![alt text](https://raw.githubusercontent.com/tjbergstrom/capstone_presentation/main/assets/07a.png)

Sentiment analysis is another great NLP project. I used the Valence Aware Dictionary and Sentiment Reasoner (VADER) which uses a lexicon and rule set tuned for analyzing social media text data. 

<br>

![alt text](https://raw.githubusercontent.com/tjbergstrom/capstone_presentation/main/assets/07b.png)

Over a time range, I take the average composite sentiment score of all comments per day, and plot the results. Scores below zero are negative, and a bove zero are positive.

<br>

![alt text](https://raw.githubusercontent.com/tjbergstrom/capstone_presentation/main/assets/08a.png)

A similar idea is to plot the sentiment score of only comments containing a specific word.

<br>

![alt text](https://raw.githubusercontent.com/tjbergstrom/capstone_presentation/main/assets/08b.png)

It's interesting to see how some words are used in comments with more negative scores than others. Here, 'vaccine' is actually not as negative as others.

<br>

### More visuals: Tracking words

<br>

![alt text](https://raw.githubusercontent.com/tjbergstrom/capstone_presentation/main/assets/09a.png)

It's helpful to see how frequently some words are used in misinformation comments over time. You can get an idea of when some trendy words come and go, while other words are always there.

<br>

![alt text](https://raw.githubusercontent.com/tjbergstrom/capstone_presentation/main/assets/09b.png)

It's fun to try plotting different words together to see how often they appear together.

<br>

![alt text](https://raw.githubusercontent.com/tjbergstrom/capstone_presentation/main/assets/09c.png)

![alt text](https://raw.githubusercontent.com/tjbergstrom/capstone_presentation/main/assets/09d.png)

![alt text](https://raw.githubusercontent.com/tjbergstrom/capstone_presentation/main/assets/09e.png)

![alt text](https://raw.githubusercontent.com/tjbergstrom/capstone_presentation/main/assets/09f.png)

As you can see in the above examples, tracking words is another great way to help track the trending themes in misinformation, and helps the team understand what's going on.

<br>

### More visuals: Comments per day

<br>

![alt text](https://raw.githubusercontent.com/tjbergstrom/capstone_presentation/main/assets/10a.png)

The available dataset makes it possible to plot how many misinformation comments have been submitted per day. It's very simple, but this was not possible with the messaging system that the team was previously using.

<br>

![alt text](https://raw.githubusercontent.com/tjbergstrom/capstone_presentation/main/assets/10b.png)

It helps the team to see this broken down by days of the week. Here, it appears they need to be ready to respond more on Wednesdays.

<br>

### Searchable database

<br>

![alt text](https://raw.githubusercontent.com/tjbergstrom/capstone_presentation/main/assets/11c.png)

All of the misinformation comments that have been collected can be displayed, and it's easy to use CTRL+F in your browser to search through the database.

<br><br><br><br>
