# Sarcasm-detection-in-news-headlines
Sarcasm detection in news headlines dataset using python

Sarcasm is "a sharp, bitter, or cutting expression or remark; a bitter gibe or taunt". Sarcasm may employ ambivalence, although it is not necessarily ironic. Most noticeable in spoken word, sarcasm is mainly distinguished by the inflection with which it is spoken and is largely context-dependent. 
Sarcasm Detection using Machine Learning has always interested in the research community. Given the nature of sarcasm, correctly identifying it in a sentence and clustering it is what makes it challenging according to research scientists. 
Sarcasm detection, when done on a twitter dataset collected using hashtag-based supervision, is prone to too much noise creation in terms of numerous labels and contextual language. To overcome this issue the dataset which we have selected is a collection created from two real news websites, the Onion, and the HuffPost. The Onion consists of news headlines with a sarcastic edge to it while the HuffPost follows a more traditional and formal path in terms of news headlines.
Advantages of using news dataset over Twitter Dataset are:
The Onion is a news website with a sole purpose of publishing sarcastic news, this helps us gain high-quality labels with very low noise compared to the twitter dataset
The News Headlines for both the websites are written by professionals in a formal manner, hence there are no spelling mistakes and informal usage of words. Such language helps in reducing the sparsity and increases the chances of finding pre-trained embeddings.
The news headlines we obtained are self-contained. It helps us in teasing apart the real sarcastic element.
Tweets and replies to the tweets are not self-contained and understanding the sarcastic element is based on the context known by a few


DATASET PROPERTIES

The Headlines Dataset consists of three attributes:
Article_link: link to the original news article
Headline: the headline of the news article
is_sarcastic: 1=sarcastic; 0=non-sarcastic

The Headlines dataset has 28619 records in total with 13634 sarcastic records and 14985 non-sarcastic records.
