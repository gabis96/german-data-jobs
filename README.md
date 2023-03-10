Data Jobs in Germany
==============================

Comming to Germany impacted my work life. I started to search for data jobs in the country but mainly in Frankfurt, and a lot of questions started arising. What are the most 'in demand' data jobs/titles/positions? Which cities have more data related job offers? What are the language requirements? 

In this project I aim to do an exploratory data analysis of the job-market related to data in Germany, and answer my questions. NLP is used to process the job descriptions to get more information of the job offers, and ML models are built to identify density in german cities.  

Roadmap
------------
1. Define Problem and Questions

2. Collect Data
    - Identify and collect the data needed and the sources to get them from.
    - If dealing with high volume of data, work with Big Data technologies.
    - Verify the acquired data is applicable and reliable.  

3. Wrangle Data
    - Explore, organize and clean the data.
    - Extract relevant information. Use NLP to extract from description.
    - Enrich the original data with added custom fields.  
    - Validate and publish data.

4. Explore Data 
    - Apply basic statistical methods to the data.
    - Plot variables┬┤ data points to identify distributions.
    - Discover correlation and causation between features.
    - Answer initial questions.

5. Model
    - Create models to represent density of each data job in german cities.
    - Evaluate models

5. Create Dashboard in Tablau

6. Build Pipeline 

Python Stack
------------
**Math & Machine Learning:** sklearn, numpy.

**Data Manipulation:** pandas (for datasets), requests & BeautifulSoup (for web scrapping).

**Visualization:** mathplotlib, plotly, geopandas, Tablau.


Data Stack
------------
**Data collection:** web scrapping.

**Data wrangling:** cleaning, structuring, enriching, and validating data.

**Exploratory Data Analisys:** descriptive statistics, correlation and causation.

**NLP:** process natural language (English & German).

**Dashboard** 

**Pipeline Deployment** 


Project Organization
------------

    ÔöťÔöÇÔöÇ LICENSE
    ÔöťÔöÇÔöÇ Makefile           <- Makefile with commands like `make data` or `make train`
    ÔöťÔöÇÔöÇ README.md          <- The top-level README for developers using this project.
    ÔöťÔöÇÔöÇ data
    Ôöé┬á┬á ÔöťÔöÇÔöÇ external       <- Data from third party sources.
    Ôöé┬á┬á ÔöťÔöÇÔöÇ interim        <- Intermediate data that has been transformed.
    Ôöé┬á┬á ÔöťÔöÇÔöÇ processed      <- The final, canonical data sets for modeling.
    Ôöé┬á┬á ÔööÔöÇÔöÇ raw            <- The original, immutable data dump.
    Ôöé
    ÔöťÔöÇÔöÇ docs               <- A default Sphinx project; see sphinx-doc.org for details
    Ôöé
    ÔöťÔöÇÔöÇ models             <- Trained and serialized models, model predictions, or model summaries
    Ôöé
    ÔöťÔöÇÔöÇ notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    Ôöé                         the creator's initials, and a short `-` delimited description, e.g.
    Ôöé                         `1.0-jqp-initial-data-exploration`.
    Ôöé
    ÔöťÔöÇÔöÇ references         <- Data dictionaries, manuals, and all other explanatory materials.
    Ôöé
    ÔöťÔöÇÔöÇ reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    Ôöé┬á┬á ÔööÔöÇÔöÇ figures        <- Generated graphics and figures to be used in reporting
    Ôöé
    ÔöťÔöÇÔöÇ requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    Ôöé                         generated with `pip freeze > requirements.txt`
    Ôöé
    ÔöťÔöÇÔöÇ setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ÔöťÔöÇÔöÇ src                <- Source code for use in this project.
    Ôöé┬á┬á ÔöťÔöÇÔöÇ __init__.py    <- Makes src a Python module
    Ôöé   Ôöé
    Ôöé┬á┬á ÔöťÔöÇÔöÇ data           <- Scripts to download or generate data
    Ôöé┬á┬á Ôöé┬á┬á ÔööÔöÇÔöÇ make_dataset.py
    Ôöé   Ôöé
    Ôöé┬á┬á ÔöťÔöÇÔöÇ features       <- Scripts to turn raw data into features for modeling
    Ôöé┬á┬á Ôöé┬á┬á ÔööÔöÇÔöÇ build_features.py
    Ôöé   Ôöé
    Ôöé┬á┬á ÔöťÔöÇÔöÇ models         <- Scripts to train models and then use trained models to make
    Ôöé   Ôöé   Ôöé                 predictions
    Ôöé┬á┬á Ôöé┬á┬á ÔöťÔöÇÔöÇ predict_model.py
    Ôöé┬á┬á Ôöé┬á┬á ÔööÔöÇÔöÇ train_model.py
    Ôöé   Ôöé
    Ôöé┬á┬á ÔööÔöÇÔöÇ visualization  <- Scripts to create exploratory and results oriented visualizations
    Ôöé┬á┬á     ÔööÔöÇÔöÇ visualize.py
    Ôöé
    ÔööÔöÇÔöÇ tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io

Initial Assumptions
------------
- Most offers state german language as a requirement.
- Berlin, Munich and Frankfurt rank hights in workers demand (meaning more job offerings in these cities).
- Berlin and Munich rank hights in english speaking job offers. 
- Data Analyst or Data Engineer rank highest in demand, comparing to Data Scientist, Machine Learning Engineer, Data Architect, etc.
- Data Science positions offer higher payments overall.
- Around 50% of Data Science job offers require a master degree.
- Hybrid mode is the tendency over on-site or from home.

Results
------------


Future Work
------------

Last Update
------------
2023-02-09 by Gabriela Rodriguez

­čöŚ Links
------------
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://gabrielarscp.wixsite.com/gabsdatascience/)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gabrielasanta/)



--------
<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
