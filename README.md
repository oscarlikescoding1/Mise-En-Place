# Mise-En-Place
CS193 Final project repository. It aims to scrape websites and generate meaningful trends and analysis. Further deatils will be added.

## The Problem:
As someone who absolutely loves cooking, there is always a struggle for me to balance 3 elements: time, taste, and cost. If something takes a short amount of time and tastes good, it's most likely expensive; if something tastes good and costs low, it probably takes a lot of time; and if something costs little and takes little time, it probably doesn't taste great. I want to build a program that will: 1) Reduce time spent finding high-quality recipes 2) Keeping taste quality high by finding reputable sources and recipe writers 3) Reduce costs by finding recipes that meet the previous 2 criteria while not requiring many additional ingredients.

## The Goal/Solution:
I want to build a program that not only scrapes high-quality recipe websites, but also use that said data to create a dataset and perform data analysis and visualization to answer questions like "what are the most common ingredients in a cuisine type?" or "what recipes can I make with the recipes I have on hand without spending too much money?" The libraries I would hope to use are pandas, numpy, sci-kit learn, and beautiful soup.

## Eisenhower Matrix:
|                    | **Urgent** | **Not Urgent** |
|    --------------  |   ------   |   ----------   |
| **Important** | <ul><li>Scrape at least one website for recipes</li><li>Obtain key information like ingredients from the website </li><li>Answer: "what are the most common ingredients in a cuisine type?"</li></ul> | <ul><li>Cost estimator that takes info from linked google sheet with available pantry ingredients</li><li>Multiple website sources and reliability weighting score for each website</li><li>A simple web interface</li></ul>|
| **Not Important** | <ul><li>HTML parsing using beautiful soup</li><li>Ingredient parsing</li><li>Unit conversions</li><li>Visualization using matplotlib</li></ul> | <ul><li>Scrapping multiple recipe websites at first</li><li>Nutrition analysis</li><li>Cuisine type classification</li></ul> |

## Technical Stack (Libraries, commands, languages, external tools etc. I plan to use):
- Python
- Pandas, Numpy, Recipe-scrapers which builds off beautiful soup, matplotlib, seaborn, ingredients-parser-nlp, rapid fuzz
- Raw recipes will be saved as json then everything stored into a csv file
- I will be pulling recipes from public recipe websites, I will be checking the specific website’s policies on web scraping then using recipe-scrapers to read it

## Milestones to be achieved:
1. Set up the github repo and environment
2. Scrape a single recipe
3. Scrape many recipes and save the raw data as JSONs
4. Parse ingredient items
5. Normalize ingredient items like green onions vs scallions
6. Build the cleaned dataset into a csv
7. Answer first question of cuisine type and ingredient rate of occurrence
8. Display basics on a simple web interface
9. Write the README and clean up

