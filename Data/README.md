This is the data folder containing both .csv files on PGA Tour data, the Jupyter Notebooks with our code, our final report, and the completed data dictionary

| **Field** | **Type** | **Description** |
| ------ | ------ | ------ |
| Player Name | Text | Golfer Name |
| Rounds | Numeric | Number of rounds played during the golf season |
| Fairway Percentage | Number | Percentage of times a golfer hit the fairway during the golf season |
| Year | Numeric | Year of Competition |
| AVG Distance | Numeric | Average driving distance during the golf season |
| Greens In Regulation (GIR) | Numeric | Percentage of greens in regulation during the golf season* |
| Average Putts| Numeric | The average number of putts taken per round, representing putting efficiency |
| Average Scrambling | Numeric | The percentage of successful recoveries after missing the green in regulation |
| Average Score | Numeric | The mean score per round across events played in a given year| 
| Points | Numeric | The total number of FedEx Cup points earned in a season |
| Performance Group | Categorical | A derived categorical variable that classifies players into “High” or “Low” performance groups based on a median split of FedEx Cup points |
