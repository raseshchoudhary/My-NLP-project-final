# My-NLP-project-final

# About the dataset.

![alt text](https://www.bootcampmedia.co.uk/wp-content/uploads/2020/09/google-serp-volatility.jpg)

The dataset is focused on political news and messages from politicians or representatives. The text column contains a tweet from the news organization NowThis News, which features a quote from Representative Trey Radel criticizing President Obama's policies related to welfare and government assistance. The other columns may provide additional context about the message and the intended audience.

# Introduction

To introduce the project I have made some basic visualizations such bar graphs and pie charts. I am using these visualization to see which source is being used most by the politicians, which sentiments are more dominating in this dataset and are they positive or negative and the share of senators and representatives in the dataset.

# Word clouds

![alt text](https://ictevangelist.com/wp-content/uploads/2015/10/IMG_0424.jpg)

In this project I have used word clouds in a very different way. Basically from a politicians view point I need to be very cautious whenever I write any message on a public platform. To solve this problem I have made world could by filtering my data. For example I filtered the data in which the dsignation was "senator", the message was "support" and the audience was "national" and then made a word cloud out it.

Now this word cloud can be used if I am a senator and I want to write a support message to the national audience. In this case I can use my word cloud to find the words that I can use in my tweets and messages.

The same can be done for other designations, audiences and messages.

# Train test split:

Afterwords I performed the train test split on my data to prepare it for further modelling. After performing this I got four values which were as follows.

1.X train

2.X test

3.Y train

4.Y test

# Converting to numbers.

![alt text](https://th.bing.com/th/id/R.03157e0a9bab9b37c718a7e143f9753f?rik=iKvfPeEA3PkK5g&riu=http%3a%2f%2fimages.soapqueen.com%2fINS%2fNumbers.jpg&ehk=zh04vrAVPJBboM%2fNzE%2fejgKXztv%2f%2by2uIMyjswZLQI0%3d&risl=&pid=ImgRaw&r=0)

In this stage I vectorized my x train and label encoded my y train, which was the categories. I had to perform this step five times as I have predicted five parameters simultaneously which are as follows.

1.AUDIENCE				

2.BIAS

3.MESSAGE

4.DESIGNATION

5.SOURCE

**Also let me mention that in this Project I have used logistic regression to make my preductions**

# Finally making a function

After going through all this hassle I finally made a function which will take any dummy string/message as an input and will give prediction on these five parameters.

1.Which type of audience is the message catering to?

2.Is the message biased or not?

3.What is the intent behind the message or the emotion>

4.What was the designation of the person who wrote the message?

5.And finally what was the source of the message?

# The end.