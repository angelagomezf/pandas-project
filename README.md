# Pandas project

---------------------------------------------

## First things first: Importing the data
I encountered a few problems when importing the data from the dataset we were given to.
I solved it seeking help from the same webpage were the dataset is from: https://www.kaggle.com/paultimothymooney/how-to-resolve-a-unicodedecodeerror-for-a-csv-file
To do so, I had to download the library "chardet" in the Terminal:

```bash
pip3 install chardet
```

## Exploring
I started exploring the dataset given to us in order to start the following step, and if I might even say, the most important part of this project: **data cleaning**.

## Data Cleaning
Oh man, this has been a challenge. My main worry was to keep as many information as possible, but without keeping too many empty values (NaN). I spent most of my time figuring out how to do this.
When using:
```python
dropna()
```
I was getting getting rid of too many useful values, and thus, my findings would have been biased.
However, when deciding to drop only the columns/rows that were *full* of NaNs I encountered a ton of problems along the way.

Another challenge I faced was replacing those empty values with something else. I thought "Unknown" was a good replacement, but then the only numerical variable I had left was turned into a categorical one. Hence, that was not an option. So I decided to replace NaN's wiht zeros, and then when cleaning variables individually, I would replace those zeros with something else.

## Graphs
When cleaning, I created a few variables with the most relevant values (eg: top_countries, top_activities, ...) in order to represent then on graphs later on. After many many tries, I haven't managed to put two of them together in the same graph, which has been very frustating.

## Conclusion
After struggling a lot with data cleaning and representing the values in order to draw conclusions from my hypotheses, I must say I an not satisfied with the final result. Nevertheless, I am looking forward to finding a solution for all the issues I have encountered along the way and can't wait to check wheter my hypotheses are true or not.


🦈🙅🏼‍♀️
