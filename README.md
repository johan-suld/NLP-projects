# Game review text classification using TF-IDF and Multinomial Naive Bayes

I created this notebook to learn more about NLP and text data analysis. Below is a very brief explanation of its content and the question being answered. Further explanation, details and the solution is presented in the notebook.

**Problem**: Based on written reviews, determine what's important for someone when it comes to recommending a PC-game to others.

**Data**: The data set consist of game reviews and a binary column which shows if the reviewer recommends it or not.

**Approach**: Train a classifier model that uses the words in the reviews as x-variables and the recommendation column as the y-variable. Analyze its features and their weights to solve the problem.

**Model selection**: Naive Bayes is chosen, partly because I've rarely used it before but also because its Multinomial type is well suited for text classification.