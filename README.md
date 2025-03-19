
# Click Through Rate Analysis
- Ads Click Through Rate is the ratio of how many users clicked on your ad to how many users viewed your ad,

- For example, 5 out of 100 users click on the ad while watching a youtube video. So, in this case, the CTR of the youtube ad will be 5%.

- Analyzing the click-through rate help companies in finding the best ad for their target audience.
## Data Sources

Acuried the data from kaggle-an open source platform(.csv format)

- https://www.kaggle.com/datasets/gauravduttakiit/clickthrough-rate-prediction?select=new_ad.csv

## Dataset Attributes

| Attribute               | Data Type  | Description |
|-------------------------|-----------|-------------|
| **Daily Time Spent on Site** | `float64`  | Time (in minutes) a user spends on the site daily. |
| **Age**                 | `int64`    | Age of the user. |
| **Area Income**         | `float64`  | Average income of the user’s area. |
| **Daily Internet Usage** | `float64`  | Time (in minutes) a user spends on the internet daily. |
| **Ad Topic Line**       | `object`   | The title or topic of the ad. |
| **City**                | `object`   | City where the user is located. |
| **Gender**              | `object`   | Gender of the user (`Male`, `Female`). |
| **Country**             | `object`   | Country of the user. |
| **Timestamp**           | `object`   | Date and time when the user interacted with the ad. |
| **Clicked on Ad**       | `int64`    | Binary (0 or 1) indicating if the user clicked on the ad. |


## Insights gained from the data.
- What is the relationship between Daily Time Spent on Site and the likelihood of clicking on an ad?

- How does Age affect the probability of clicking on an ad?

- Is there a correlation between Daily Internet Usage and Ad Clicks?

- Do users with higher Area Income spend more time on the site?

- Which age group has the highest engagement with ads?

- Does Gender play a role in ad engagement?
- Are there certain Countries where users are more likely to click on ads?
- Does the City influence Daily Time Spent on Site or Ad Clicks?

- Is there a specific time of the day (based on Timestamp) when users click on ads the most?


## Model Architecture


![App Screenshot](https://github.com/Ram-Pathuri/Ads-Click-Through-Rate-/blob/main/Screenshot%202025-03-19%20175506.png)



We used several ml models to gain the high accuracy


## Metrics


| Model Name            | Accuracy (%) | 
|-----------------------|-------------|
| Logistic Regression  | 69.5        |
| Decision Tree       | 77.05       |
| Random Forest       | 80.55       |

## Model Interpration
## Model Deployment
## Screenshots
