# Company Classification
Problem Statement : We are given with web scraped data of various businesses and companies. We need to somehow categorize these businesses and companies across a standard taxonomy (consists of term names and labels that are specific to an organization's information and unique to how that business operates). So that, business can leverage this information and target potential companies.
<br><br>
<a href="https://drive.google.com/drive/folders/1yGu1w7UjV4Ml7ew_R83pBikgMNgIFKTh">Access the DataSet Here</a>
# Overview of the DATASET
Website: The website of the company/business

Company Name: The company/business name

Homepage Text : Visible homepage text

H1: The heading 1 tags from the html of the home page

H2: The heading 2 tags from the html of the home page

H3: The heading 3 tags from the html of the home page

Navlink text: The visible titles of navigation links on the homepage (Ex: Home, Services, Product, About Us, Contact Us)

Meta keywords: The meta keywords in the header of the page html for SEO

Meta description: The meta description in the header of the page html for SEO

We used Kmeans clusternig on the sparse matrix that we got after TF-IDF vectorization to create word clouds that can tell which company it belongs to as an example we have our Healthcare sector as:

<img src = "https://user-images.githubusercontent.com/75989898/118387620-ffc00780-b63c-11eb-884f-534657116ced.PNG" width ="600"/>

# Files Description
Company Classification.ipynb: Python notebook with all the Data Preprocessing and Clustering code. It can be used in Jupyter Notebook or in Google Colab.
presentation.pdf: Presentation of the project.
