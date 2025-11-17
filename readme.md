# PowerBI reports
These reports are just for fun and to train building PowerBI reports and semantic models. 

The datasets, available on [/sources/](https://github.com/RoboticPea/powerbi/tree/main/sources), are available online on platforms like [Microsoft Learn](https://learn.microsoft.com/en-us/power-bi/create-reports/sample-datasets) and [Kaggle](https://www.kaggle.com/datasets). In some cases, I created additional dimensions to help me with the visuals or navigation options I intended to use.

See more project ideas [here](https://www.projectpro.io/article/power-bi-microsoft-projects-examples-and-ideas-for-practice/533).

## Streaming
This report contains information for Netflix, Amazon Prime and Disney+ shows. The data is filtered so that the report only has shows that were released as early as 2010. 

For the report I wanted to make, I created two separate dimensions to group both ratings and genre in a more recognizable label and to help with visuals.

I also created two new measures for duration, one for movies and the other for tv shows, to also group data in a way that would bring more information by simplifying the visuals. I needed to segregate between movies and tv shows because the duration of a tv show was by seasons, whereas for movies was by minutes.
