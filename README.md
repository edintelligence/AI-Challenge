# AI-Challenge

### Data sets finding resources:

https://deeplearning4j.org/opendata

https://elitedatascience.com/datasets

https://en.wikipedia.org/wiki/List_of_datasets_for_machine_learning_research

https://aws.amazon.com/datasets/  (quality data sets)

https://github.com/fivethirtyeight

https://github.com/BuzzFeedNews

https://opendata.socrata.com/ clean data

https://www.reddit.com/r/bigquery/wiki/datasets BIG data by google

### Selected dataset

------------------------------------------

https://www.kaggle.com/hacker-news/hacker-news

#### *nlp, news*

This dataset contains all stories and comments from Hacker News from its launch in 2006. Each story contains a story id, the author that made the post, when it was written, and the number of points the story received. Hacker News is a social news website focusing on computer science and entrepreneurship. It is run by Paul Graham's investment fund and startup incubator, Y Combinator. In general, content that can be submitted is defined as "anything that gratifies one's intellectual curiosity".

------------------------------------------

https://www.kaggle.com/datasnaek/mbti-type

#### *psychology, nlp*

This dataset contains over 8600 rows of data, on each row is a person’s:
    • Type (This persons 4 letter MBTI code/type)
    • A section of each of the last 50 things they have posted (Each entry separated by "|||" (3 pipe characters))

------------------------------------------

https://www.kaggle.com/zalando-research/fashionmnist

Each image is 28 pixels in height and 28 pixels in width, for a total of 784 pixels in total. Each pixel has a single pixel-value associated with it, indicating the lightness or darkness of that pixel, with higher numbers meaning darker. This pixel-value is an integer between 0 and 255. The training and test data sets have 785 columns. The first column consists of the class labels (see above), and represents the article of clothing. The rest of the columns contain the pixel-values of the associated image.
    • To locate a pixel on the image, suppose that we have decomposed x as x = i * 28 + j, where i and j are integers between 0 and 27. The pixel is located on row i and column j of a 28 x 28 matrix.
    • For example, pixel31 indicates the pixel that is in the fourth column from the left, and the second row from the top, as in the ascii-diagram below. 

------------------------------------------

https://www.kaggle.com/keplersmachines/kepler-labelled-time-series-data

#### *space, continuous, time series analysis*

The data describe the change in flux (light intensity) of several thousand stars. Each star has a binary label of 2 or 1. 2 indicated that that the star is confirmed to have at least one exoplanet in orbit; some observations are in fact multi-planet systems.
As you can imagine, planets themselves do not emit light, but the stars that they orbit do. If said star is watched over several months or years, there may be a regular 'dimming' of the flux (the light intensity). This is evidence that there may be an orbiting body around the star; such a star could be considered to be a 'candidate' system. Further study of our candidate system, for example by a satellite that captures light at a different wavelength, could solidify the belief that the candidate can in fact be 'confirmed'.

------------------------------------------

https://www.kaggle.com/zillow/zecon

#### *continuous, housing, sales*

Zillow's Economic Research Team collects, cleans and publishes housing and economic data from a variety of public and proprietary sources. Public property record data filed with local municipalities -- including deeds, property facts, parcel information and transactional histories -- forms the backbone of our data products, and is fleshed out with proprietary data derived from property listings and user behavior on Zillow.
The large majority of Zillow's aggregated housing market and economic data is made available for free download at zillow.com/data.

------------------------------------------

https://www.kaggle.com/muonneutrino/us-census-demographic-data

This dataset expands on my earlier New York City Census Data dataset. It includes data from the entire country instead of just New York City. The expanded data will allow for much more interesting analyses and will also be much more useful at supporting other data sets.

------------------------------------------

https://www.kaggle.com/kemical/kickstarter-projects

https://www.kaggle.com/codename007/funding-successful-projects

#### *kickstarter, nlp* 

I'm a crowdfunding enthusiast and i'm watching kickstarter since its early days. Right now I just collect data and the only app i've made is this twitter bot which tweet any project reaching some milestone: @bloomwatcher . I have a lot of other ideas, but sadly not enough time to develop them... But I hope you can!

------------------------------------------

https://www.kaggle.com/residentmario/wheres-waldo

#### *vision, image recognition*

Where's Waldo is a popular children's book series where the reader is presented with a sequence of scenes. Each scene contains potentially hundreds of individuals doing different things. Exactly one of these figures is Waldo: a tall man in a striped red shirt, red beanie, and glasses, and the objective of the game is to find Waldo is the least time possible. This dataset is raw data from the books for these challenges.

------------------------------------------

https://www.kaggle.com/ritresearch/happydb

#### *unstructured text nlp*

HappyDB is a corpus of more than 100,000 happy moments crowd-sourced via Amazon’s Mechanical Turk.
Each worker is given the following task: What made you happy today? Reflect on the past 24 hours, and recall three actual events that happened to you that made you happy. Write down your happy moment in a complete sentence. (Write three such moments.)
The goal of the corpus is to advance the understanding of the causes of happiness through text-based reflection.
More information is available on the HappyDB website (https://rit-public.github.io/HappyDB/).

------------------------------------------

https://www.kaggle.com/bharadwaj6/kindle-reviews

#### *sentiment analysis, nlp, reviews*

A small subset of dataset of product reviews from Amazon Kindle Store category.

------------------------------------------

https://www.kaggle.com/crawford/emnist

#### *vision, deep learning, mnist*

The EMNIST dataset is a set of handwritten character digits derived from the NIST Special Database 19 and converted to a 28x28 pixel image format and dataset structure that directly matches the MNIST dataset. Further information on the dataset contents and conversion process can be found in the paper available at https://arxiv.org/abs/1702.05373v1.


------------------------------------------

https://www.kaggle.com/rounakbanik/the-movies-dataset


These files contain metadata for all 45,000 movies listed in the Full MovieLens Dataset. The dataset consists of movies released on or before July 2017. Data points include cast, crew, plot keywords, budget, revenue, posters, release dates, languages, production companies, countries, TMDB vote counts and vote averages.
This dataset also has files containing 26 million ratings from 270,000 users for all 45,000 movies. Ratings are on a scale of 1-5 and have been obtained from the official GroupLens website.

------------------------------------------

https://www.kaggle.com/derrickmwiti/24-thousand-tweets-later

#### *twitter, nlp, sentiment*

I collected this data from incubators and accelerators to find out what they have been talking about in 2017.


------------------------------------------


https://www.kaggle.com/fuzzyfroghunter/dickens

#### *nlp*

his is a collection of all the works of Charles Dickens that are available through Project Gutenberg.
This dataset is subject to the Project Gutenberg license.
It is very possible that I have missed some of his works. Please add them and update the "Last updated" date below if you get the chance. Otherwise, if you leave a comment on this dataset, I will try and do so myself.
I did some very rough deduplication of his works. If I missed anything, please call it out with a comment and I will rectify the situation.

------------------------------------------

https://www.kaggle.com/philipjames11/dark-net-marketplace-drug-data-agora-20142015

#### *market place analysis*

This data set was made from an html rip made by reddit user "usheep" who threatened to expose all the vendors on Agora to the police if they did not meet his demands (sending him a small monetary amount ~few hundred dollars in exchange for him not leaking their info). Most information about what happened to "usheep" and his threats is nonexistent. He posted the html rip and was never heard from again. Agora shut down a few months after. It is unknown if this was related to "usheep" or not, but the raw html data remained.
Content
This is a data parse of marketplace data ripped from Agora (a dark/deep web) marketplace from the years 2014 to 2015. It contains drugs, weapons, books, services, and more. Duplicate listings have been removed and prices have been averaged of any duplicates. All of the data is in a csv file and has over 100,000 unique listin

------------------------------------------

https://www.kaggle.com/borismarjanovic/price-volume-data-for-all-us-stocks-etfs

#### *financial, continuos*

High-quality financial data is expensive to acquire and is therefore rarely shared for free. Here I provide the full historical daily price and volume data for all U.S.-based stocks and ETFs trading on the NYSE, NASDAQ, and NYSE MKT. It's one of the best datasets of its kind you can obtain.

------------------------------------------

https://www.kaggle.com/unitednations/un-general-debates

#### *nlp, debate analysis*

very year since 1947, representatives of UN member states gather at the annual sessions of the United Nations General Assembly. The centrepiece of each session is the General Debate. This is a forum at which leaders and other senior officials deliver statements that present their government’s perspective on the major issues in world politics. These statements are akin to the annual legislative state-of-the-union addresses in domestic politics. This dataset, the UN General Debate Corpus (UNGDC), includes the corpus of texts of General Debate statements from 1970 (Session 25) to 2016 (Session 71).

------------------------------------------

https://www.kaggle.com/kmader/mias-mammography

#### *computer vision, image recognition*

The data is images and labels / annotations for mammography scans. More about the database can be found at MIAS. The 'Preview' kernel shows how the Info.txt and PGM files can be parsed correctly.

------------------------------------------

https://www.kaggle.com/mloey1/ahcd1

#### *image recognition*

Handwritten Arabic character recognition systems face several challenges, including the unlimited variation in human handwriting and large public databases. In this work, we model a deep learning architecture that can be effectively apply to recognizing Arabic handwritten characters. A Convolutional Neural Network (CNN) is a special type of feed-forward multilayer trained in supervised mode. The CNN trained and tested our database that contain 16800 of handwritten Arabic characters. In this paper, the optimization methods implemented to increase the performance of CNN. Common machine learning methods usually apply a combination of feature extractor and trainable classifier. The use of CNN leads to significant improvements across different machine-learning classification algorithms. Our proposed CNN is giving an average 5.1% misclassification error on testing data.

------------------------------------------

https://www.kaggle.com/rtatman/handwritten-mathematical-expressions

####  *image recognition, interesting problem*

If you've ever had to typeset mathematical expressions, you might have thought: wouldn’t it be great if I could just take a picture of a handwritten expression and have it be recognized automatically? This dataset has all the data you’ll need to build a system to do just that.

------------------------------------------

https://www.kaggle.com/artimous/every-song-you-have-heard-almost

#### *song analysis*

One fine day, when someone with the idea of self sufficient AI capable of writing it's own poems wanted data, he stumbled upon the idea of using songs as a source. The journey wasn't easy, since each song has it's own page with the lyrics and scraping pages one at a time (when there are over a million of them) is a slow task. I worked up some optimisations here and there. For people interested in going through the process:

------------------------------------------

https://www.kaggle.com/gabrio/board-games-dataset

#### *sales, reviews*

A dataset containing the attributes and the ratings for around 94,000 among board games and expansions as get from BoardGameGeek.

