covid19_mask_sentiment
==============================

A covid-19 mask sentiment analysis inspired by a conflict of information presented online and offline regarding mask effectiveness and if one should wear one. This is an active tracking project and I built a publicly accessible app for monitoring the data. 

You can visit the app [here](https://covid19-mask-sentiment.herokuapp.com/).  

You can also read more about the project on [Medium](https://medium.com/p/a104170ad9a7/edit).  


![AppImage](https://steam-discount-predictor.s3-us-west-2.amazonaws.com/static/app_pic.JPG)

------------
### Topic Modeling + Cluster Findings:


![Findings](https://steam-discount-predictor.s3-us-west-2.amazonaws.com/static/findings.jpg)

------------
Project Organization
------------

    ├── LICENSE
    ├── README.md        
    ├── data
    │   ├── processed      <- Processed historical tweet data (1/1 to 5/1, 2020)
    │   └── raw            <- Raw historical data.
    │
    ├── models             <- Contains trained Kmeans Cluster Model and specialized word2Vec model.
    │
    ├── notebooks          <- Majority of the code is here, I may add some more steps in "Historical Data Analysis" as it doesn't fully     │                         reflect all the steps I have taken.
    │
    ├── presentation       <- presentation made for this project.
    │
    └── requirements.txt   <- The requirements file for reproducing the analysis environment.
     
--------

### Useful resources to build the dash-flask app:

[Live graph tutourial by Sentex on Youtube](https://www.youtube.com/watch?v=bz2zqXFjOrE)  

[Plotly Dash official examples](https://dash-gallery.plotly.host/Portal/)  

--------
Thank you.
