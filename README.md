# YelpRecommendation

Yelp Recommendation will be used with Mongo DB 
You can follow the instructions below to install it.
https://docs.mongodb.com/v3.4/installation/#tutorials

To get the Yelp Dataset you will need to signup and download the json files
https://www.yelp.com/dataset/download

After this run following commands to insert json files into mongodb

mongoimport  --db Yelp --collection user --file ~/DataMining/Project/user.json

mongoimport  --db Yelp --collection business --file ~/DataMining/Project/business.json

mongoimport  --db Yelp --collection reviews --file ~/DataMining/Project/review.json

mongoimport  --db Yelp --collection tips --file ~/DataMining/Project/tip.json

For running the ContentBasedRecommendation system run following command

python contentBasedRecommendation.py





