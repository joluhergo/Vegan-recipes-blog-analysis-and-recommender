# Vegan-recipes-blog-analysis-and-recommender
Data Analysis and menu recommender based on the Spanish blog "Danza de Fogones", developed for the Ironhack's final project.

# Motivation and project description:

Protein intake in a vegan diet is often presented as an issue that conditions the relationship with food and sometimes represents a barrier for those who consider this type of diet.

For this project I conducted an independent analysis of the popular blog "Danza de Fogones", trying to answer the following question: will I meet my nutritional needs if I eat random recipes from this blog over time?

The data is taken from the recipes published on the website. The analysis is based on a dataset created by me by combining the dishes that could be eaten over 5,000 days, combined in a completely random way.

#Challenges:

The structure and content of the blog have made it difficult to obtain data. In addition, it turned out that more than 35% of the recipes did not contain the necessary information for the analysis.

# Content and how to use

There are three notebooks. The first one contains code necessary for Web Scraping. The result of this notebook is the file fogones_scraped_df_df_2.csv

The second notebook contains the cleaning process and the recommender. You need to use the previous csv file. The reason why the cleanup is separated is to avoid making more requests than necessary to the web page.

The third notebook contains the data analysis based on the 5.000 menus generated in the previous notebook. You need to use the random_5000_recipes.csv document.

A Streamlit application with this recommender will be available in the next days.

# Copyright

Feel free to use these files, please always with a quote to the source and the original work: this repository and the recipes from which the data was extracted.
I have not used the content of the recipes, only the name, to avoid possible plagiarism and to encourage the original source to be consulted. 

Author: Jose Hernández
