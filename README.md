# SPACEX-Machine-Learning-Project

This project was completed in order to attain the IBM Data Science Professional Certificate. 

Space X advertises Falcon 9 rocket launches on its website at a cost of 62 million dollars, while other providers charge upward to 165 million dollars each. Much of the savings is because Space X can reuse the first stage - the bottom part of the rocket that is released during launch -, provided it is landed succesfully. Therefore, if we can determine if the first stage will land, we can determine the approximate cost of that launch. This information can be used if an alternate company wants to bid against space X for a rocket launch.

Keeping that in mind, the purpose of this project was to implement machine learning models to try to predict whether the first stage will land succesfully or not - a classification problem -, based on features both of the rockets and the launch sites.

Each jupyter notebook contains a different step of the analysis:
1) Data collection through SPACEx Public APIs
2) Data collection through Web Scraping of Wikipedia
3) Data wrangling with Pandas library
4) Exploratory Data Analysis (EDA) with SQL, using the sqllite module
5) EDA through data visualization with Seaborn library
6) Interactive maps of the SPACEX Launch Sites and their proximities with Folium library
7) Interactive dashboards built with Plotly-Dash libraries
8) Machine Learning Classification (logistic regression, support vector machines, decision trees, K-Nearest Neighbors)
