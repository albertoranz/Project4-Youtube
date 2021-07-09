<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# YouTube Trending Analysis
Alberto Ranz

DA, RT, FT, May2021


### Content
- [Project Description](#Project-Description)
- [Questions & Hypotheses](#Questions-&-Hypotheses)
- [Dataset](#Dataset)
- [Workflow](#Workflow)
- [Organization](#Organization)
- [Links](#Links)


## Project Description
YouTube is the biggest online video platform today. In its Trending section it recommends videos according to specific characteristics that can be analysed. In this project, a dataset of these trending videos for several countries is observed trying to obtain conclusions about the videos and the platform.


## Questions & Hypotheses
- Which categories get more comments, likes and views? Which categories get less? Per country.
- Which categories have more trending videos? Which ones have less?
- Is there a correlation between video categories and season or month of publication/date of trend? It could be interesting to find patterns of video success depending on category and publication date, for example to predict in which date it is better to publish a music video.
- How much time does normally a video take since it is published until it trends? Is this related to its category? Can we make predictions?
- Which kind of video titles trend more, longer or shorter ones?
- Is there a relation between tags of a video and its trending? Do videos with more tags trend more?
- Does comment deactivation and/or rating deactivation make an influence in trendings?
- How many likes and views have trending videos in each country? Which countries have more likes and views in their trends?
- How many comments have trending videos in average?


## Dataset
I used a dataset from Kaggle that was scraped from YouTube's API. https://www.kaggle.com/datasnaek/youtube-new
The dataset is composed of 10 tables, each for a different country, containing data like number of views, likes, comments, date of trend, and many more.


## Workflow
I firstly observed the tables to understand the kind of information I was going to work with. After that, I cleaned and ordered the tables, making new ones from the originals, to make the work easier and faster. Then, I performed the calculations needed to answer my questions, and finally I made the visualizations in Tableau.
 
 
## Organization
I used the Trello board for organizing the whole project.

My repo contains the main code jupyter notebook file and three folders. The first folder (archive) contains the downloaded datasets, the second folder (newdfs) contains the tables I created for the project, and the third one contains images of the plots.


## Links
Include links to your repository, slides and kanban board. Feel free to include any other links associated with your project.

[Repository](https://github.com/albertoranz/Project4-Youtube)

[Trello](https://trello.com/b/66UwLNBt/project-4-youtube-trends)

[Dataset](https://www.kaggle.com/datasnaek/youtube-new)
