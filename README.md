# Viet Hung Bui's individual project report

## Introduction 
The objective of this project is to practice using Jupiter Notebook. The World Cup 2022 is happening in Qatar. It catches the eye of millions of people in the world and I am a fan of soccer as well so, I choose this topic for my final project in Data Science Fundamental so that It satisfies my passion and I can improve my skills for this Data Science Fundamental class.

When I looked at the dataset. It was so many information and I wondered to myself that how can I know the winner of each world cup from the beginning up to now or how can I know the hosting of each world cup. Then I narrow down each table and get the result by the skills that I’ve learn in this class. Besides that, I’ve learn how to visualize the data so that it will be easier to present for other people.  

## Selection of data 
The model processing and training are conducted using a Jupiter Notebook.

There are three datasets: 
- `wcmatches.csv`. This dataset include 15 features such as `year`,`country`,`city`,...

Data preview: 
![Picture 1](set1.png)
- `worldcups.csv`. This dataset include 10 features such as `year`,`host`,`winner`,....

Data preview: 
![Picture 2](set2.png)
- `worldcup_goals.csv`. This dataset include 3 features such as `player`, `year`,`goals`

Data preview: 
![Picture 3](set3.png)
The main outcome are extracting and visualization data. The dataset can be found online at 
[kaggle](https://www.kaggle.com/datasets/evangower/fifa-world-cup)[1]

## Methods
- Pandas
  - Read CSV file
  - Extract data 
- Seaborn
  - Scatterplot
- Plotly
  - Scatter
  - Visualization
## Results
- The Winners from 1930 to 2018 World Cup:
 
![Picture 4](firstplace.png)

- The Second-place from 1930 to 2018 World Cup:

![Picture 5](secondplace.png)

- The Third-place from 1930 to 2018 World Cup:
 
![Picture 6](thirdplace.png)

- The Fourth-place from 1930 to 2018 World Cup: 

![Picture 7](fourthplace.png)

- Summary: 
  - 1st. Brazil won 5 World Cup titles, 2 2nd-places, 2 3rd-places, 2 4th-places. 
  - 2nd. Italia won 4 World Cup titles, 2 2nd-places, 1 3rd-places, 1 4th-places. 
  - 3rd. Germany won 3 World Cup titles, 3 2nd-places, 1 4th-places.

- Visualization the World Cup Winner:

![Picture 8](visualwinner.png)

- The number of attendances at each World Cup from 1930 to 2018: 

![Picture 9](attendances.png)

- The year and the number of Goal-Scored from 1930 to 2018 World Cup: 

![Picture 10](year-goals.png)

- Visualization the year and goals-scored: 

![Picture 11](year-goals-visual.png)

- The frequence of the host countries: 

![Picture 12](freq-host.png)

- The countries who hosted and won the World Cup:

![Picture 13](host-win.png)

- The player who scored most in World Cup: Miroslav Klose with 16 goals 

![Picture 14](top-goals.png)


## Discussion 
- The answer help me summary the entire data about FIFA World Cup in the range from 1930 - 2018. 
- I can find these information easily by Google. However, with the Visualization, it helps me to have more dimension about data. 
- In the future, with these data I may predict the winner of the World Cup by using Poison Distribution.   

## References
[1][World Cup dataset](https://www.kaggle.com/datasets/evangower/fifa-world-cup)
