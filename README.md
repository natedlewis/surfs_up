# surfs_up

## Overview
We have been asked by W. Avy to analyze some weather data from Oahu, Hawaii in order to assure the desired location of her Surf & Ice Cream is a good fit. We'll be using SQLite to store the weather data that W. Avy shared with us for proper analysis. SQLAlchemy will then provide us a connetion to the database, and will act as our primary tool throughout this project for its ability to query.

## Results
June Temperatures             |  December Temperatures
:-------------------------:|:-------------------------:
![june_df](https://github.com/natedlewis/surfs_up/blob/main/june_df.png?raw=true)  |  ![dec_df](https://github.com/natedlewis/surfs_up/blob/main/dec_df.png?raw=true)


- The average temperatures among the two months differ by just 4°F.
- 50% of December days either experience temps below 69°F, or reach average June temps of 74°F. 
- Decemeber temps deviate by 0.5°F more than those of June.
- They share similar highs, but the coldest days of December are much colder.
- The low temp of 56°F within December could be a signal to the slight disprecency in standard deviations.
- The weather in Oahu seems to experience little variance among seasons. However, we would need further data to feel comfortable making such claim.

