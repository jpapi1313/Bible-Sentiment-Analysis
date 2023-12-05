**# Bible-Sentiment-Analysis**
A collection of python code analyzing the sentiment and word usage in different translations of the bible.

There are many translations of the bible. Some are literal word for word translations, some care more about literal meanings, and some are paraphrased. My question was, "Do these translations convey a considerable diffence in tone from one another?" By applying a sentiment analysis on each verse we can answer this question. The source data is each bible in a raw text file that I got from https://openbible.com/texts.htm. At first I wrote this to analyze one at a time but once I did that I decided to make it itterate over the whole list. It must have been fairly intensive because it took my 1260p 16G ram machine over 24 minutes to run through it. Not sure if that's good or bad considering it was roughly 342, 144 individual verses.
The comments in the code should be enough to get the gist of what I was doing.

![image](https://github.com/jpapi1313/Bible-Sentiment-Analysis/assets/43052472/5c576d41-a957-4730-b799-177a777d3d73)
![image](https://github.com/jpapi1313/Bible-Sentiment-Analysis/assets/43052472/564920e0-fb53-46fe-b7b0-26f44d2a475e)



After viewing these two visuals we can determine that they do vary slightly in their overall sentiment. The slight variation is likely due to the translators word choice being graded more kindly or harshly than the others by the sentiment function. I was hoping to see some stark differences that I could investigate but as we didn't get that, I won't dive further into it at this point.
Fun Fact--There are around 31,102 verses in the bible, give or take a few depending on the translation.
