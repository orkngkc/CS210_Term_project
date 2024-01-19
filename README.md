# CS210_Term_project Orkun Efe Gökçe ID:31045

In this project i have analysed my own spotify streaming history and search queries. About streaming history, there are lots of useful insights, I have analysed my favorite artist among the last year, and dive into some detailed analysis. Also there is a sentiment analysis part in the project for english and turkish songs, but for turkish songs I couldn't find any model that can analyse the whole lyrics, mostly they are capable of analysing a string with length 512. For English sentiment analysis I have used TextBlob and for Turkish I used BERTurkish. Mostly I have used matplotlib to viusalise the findings. If you want to use this code yourself the whole code is usable for any spotify streaming history data when you change the directory of the json files, and also you have to modify Spotipy and Lyricgenius credidentials, because I will be deactivating them. Exploratory Data Analysis part is mostly giving insights about the most common artist in different periods, also the top genres in last year, also the streaming habits througout the Finals periods and Holiday Periods.

![HabitSeasonal](https://github.com/orkngkc/CS210_Term_project/assets/115142137/78e40b19-af5c-4c19-b3e1-ee1bb4702996)

![ListeningMonth](https://github.com/orkngkc/CS210_Term_project/assets/115142137/3462bd95-dacb-4ac2-9db8-4aaa88f54061)

![top10Year](https://github.com/orkngkc/CS210_Term_project/assets/115142137/b79b0503-0514-4fdb-be34-ef6a7e79f16d)



Furthermore there is a sentiment analysis part, I have fetched the lyrics of the songs that I have listened and made a sentiment analysis on them, My hypothesis was changed since the proposal because the data was not capable of answering the first Hypothesis. My hypothesis is, Our streaming habits are changing according to our emotional conditions for example in summer we are tending to listen more positive vibed songs since we are more outgoing and more energetic. Sentiment Analysis is supporting that hypothesis as can be seen in the related chart on the notebook. 

![sentimentSeasonal](https://github.com/orkngkc/CS210_Term_project/assets/115142137/b44a9d5f-23bd-4d39-83f5-00ef15bc7cc8)
![sentimentMonthly](https://github.com/orkngkc/CS210_Term_project/assets/115142137/871da795-f9a1-4108-943c-30238e1b8ec9)


Lastly for sentiment analysis I needed to detect the languages of songs in order to apply the correct language model for analysis, and I used pythons langdetect language for it.

Here is the short (4 minutes) video for the presentation of the project: https://drive.google.com/file/d/1r29tYEWERllVAd9s0wkdMdV-xWDI4Uai/view?usp=sharing

Thank you in advance for sparing your valuable time,
Best Regards

Orkun Efe Gökçe


