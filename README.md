# Swiss Hospital Assistant



![alternative text](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRnzH-O7qsG29l9Gv7t6i26QRsf2mvvIqB40A&usqp=CAU)


#### -- Project Status: [Completed]

## Project Intro/Objective
We enable medical practitioners to place the right services, at the right location. Some regions will need more attention from Cardiologists. Other, from Gynecologists. Knowing which diseases affect the population enables you to place the right medical cabinet at the right place. In this project, we will model the disease distribution for any region in Switzerland. We will also show which hospitals are qualified at treating it and which places require further medical staff and equipment.

### Partner
* [SIT academy](https://sit.academy/)
* [NXGEN Medical Services](https://nms.health/)

### Methods Used
* Inferential Statistics
* Machine Learning
* Data Visualization
* Data cleaning and processing

### Technologies
* Python
* geojson
* plotly, seaborn, matplotlib
* Pandas, numpy, google colab
* Regular Expressions
* DeepL api for translations
* streamlit

## Project Description 

The objective of this project was to create an application which can analyze patient distribution in specific cantons to help Swiss hospitals improve their treatment options. Moreover, we provide further information concerning the number of patients in various disease groups in these hospitals and the service they provide.
The project was carried out in collaboration with NXGEN Medical Services, a startup company that specializes in data collection, machine learning, and predictive analysis. 
Our workflow included three vital steps: collecting real-world data from various sources, processing them, and uploading them to the company database. The cleaning process was the most challenging and important one for many reasons. The data we acquired contained information in German, French, and Italian, so the first step was to use deep learning to translate them to English. The next step was to extract information from a source which contained multiple types of inputs in one column without a distinct pattern. All these steps were implemented in a pipeline with the aim to allow an easy insertion of future data into the company database. This way, the app can remain up to date with the latest datasets provided. Furthermore, we analyzed the data at hand using statistical tools, visualization, and machine learning. These tools were the essential components of the interactive app we created on Streamlit to make the data we extracted accessible and easy for the hospitals to use.

[Streamlit link:](https://share.streamlit.io/ansamz/hospitals-and-diseases-in-switzerland/main/notebooks/AZ-streamlit.py)

For example, the graph below contains the following information: the number of patients per hospital according to the disease category, the city and canton where the hospital is located, and the population number. In our app, you can hover over cities to display more information:

![alternative text](/screenshot/Screenshot_20220503_102849.png)

Additional information about the most prevalent diseases per region, birth rates, specialized medical equipment, and staff members was added as well.
In the future, we are hoping that this data will help build an app designated for patients to help them find the best and nearest medical facility to treat their illness. Furthermore, it could help in creating an algorithm to analyze and rate the quality of hospitals based on many features of the data provided, i.e., mortality, transferring patients to a different hospital due to lack of specialized doctors or equipment, length of stay at the hospital, and so on and so forth. 
This app will improve the quality of medical treatment, especially in the peripheral areas, and hopefully increase the availability of medical equipment.


## Data

1. [Medical Statistics of swiss hospitals](https://www.bfs.admin.ch/bfs/de/home/statistiken/kataloge-datenbanken/tabellen.assetdetail.20044205.html)
2. [Ouality indicators, contains metadata as well](https://www.bag.admin.ch/bag/de/home/zahlen-und-statistiken/zahlen-fakten-zu-spitaelern/qualitaetsindikatoren-der-schweizer-akutspitaeler/qualitaetsindikatoren-dokumentation.html)
3. [Swiss Hospitals](https://www.bag.admin.ch/bag/de/home/zahlen-und-statistiken/zahlen-fakten-zu-spitaelern/kennzahlen-der-schweizer-spitaeler.html)
4. [Medical data according to age group](https://www.bfs.admin.ch/bfs/de/home/statistiken/kataloge-datenbanken/tabellen.assetdetail.20044114.html)
5. [Birth rates in Switzerland](https://www.bfs.admin.ch/bfs/de/home/statistiken/kataloge-datenbanken/tabellen.assetdetail.21826833.html)
6. [C section rates in Switzerland](https://www.bfs.admin.ch/bfs/de/home/statistiken/kataloge-datenbanken/tabellen.assetdetail.20044115.html)
7. [Hospitalization according to canton](https://www.bfs.admin.ch/bfs/de/home/statistiken/kataloge-datenbanken/tabellen.assetdetail.20044061.html)


## Getting Started

1. Clone this repo (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. Raw Data is being kept [here](Repo folder containing raw data) within this repo.

    *If using offline data mention that and how they may obtain the data from the froup)*

3. Data processing/transformation scripts are being kept [here](Repo folder containing data processing scripts/notebooks)
4. etc...

*If your project is well underway and setup is fairly complicated (ie. requires installation of many packages)
create another "setup.md" file and link to it here*

5. Follow setup [instructions](Link to file)

## Featured Notebooks/Analysis/Deliverables
* [Notebook/Markdown/Slide Deck Title](link)
* [Notebook/Markdown/Slide DeckTitle](link)
* [Blog Post](link)


## Contributing Members

 - [Zuzana Dostalova](https://github.com/zuzanadostalova)
 - [Ansam Zedan](https://github.com/ansamz)
