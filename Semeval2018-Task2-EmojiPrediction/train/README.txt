Quick start:
1) Download the json of the tweets with the crawler, see the README in the crawler folder. 
2) Prepare the dataset for the emoji prediction task using the emoji extractor. Run it with:
python2.7 emoji_extractor_semeval18.py PATH/TO/JSON.txt LANGUAGE(us|es)

For example (for us):
python2.7 emoji_extractor_semeval18.py ./crawler/data/tweet_by_SOMEDATE.txt us

For example (for es):
python2.7 emoji_extractor_semeval18.py ./crawler/data/tweet_by_SOMEDATE.txt es

After the execution, you will find three files in the same folder of the twitter json:
- .text file with one text per line
- .labels file with one label per line (same order as previous one)
- .ids file with one twitter id per line (to keep track of the tweet you are using)

Good luck! For any issue ask us a question in the google group:
https://groups.google.com/d/forum/semeval-2018-task-2-multilingual-emoji-prediction