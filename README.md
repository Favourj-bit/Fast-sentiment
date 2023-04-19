# Fast-sentiment

I built an NLP model to test the sentiment of sentences and words. This was done using
VaderSentiment. It was deployed using docker and fastapi

![image](https://user-images.githubusercontent.com/63251266/193255781-8cc0a910-f431-4da9-a9bd-bb8bcec6333d.png)

To test the API
1. Make sure docker is installed, I installed docker desktop
2. run the command: docker build -t fast_sentiment .
3. run the command: docker run -p 8000:8000 -t -i fast_sentiment
4. Visit http://localhost:8000/docs to interact with the API

NB: These commands are for window users, if using Linux, you will need to include sudo to the front of the commands
