# TwitterDataAnalysis
Twitter Data Analysis  is a software that scrapes data from twitter and analyses the data scraped to obtain useful information

# Getting Started
- To run on local machine git  clone this project:

```
$ git clone https://github.com/hun3/TwitterDataAnalysis.git
```
 copy and paste the above command in your terminal, the project will be downloaded to your local machine
 
 ## Prerequisites
 The application is built using python: django framework
 
 To install python checkout:
 ```
 https://www.python.org/
 ```
 
 ### installing
 For this section I will assume you have python3 and it is configured on your machnine. </br>
 Navigate to the folder you cloned and run: </br>
 
 -Install Requirements
 ```
 $pip install -r requirements.txt
 ```
 
 - Configure database
 ```
 $ cd Datascraper
 $ python manage.py makemigrations
 $ python manage.py migrate
```

## Session Examples
Run App 🏃🏃‍ with the script bellow to start the server
```
$ python manage.py
```
- Profile Analysis 
Navigate to ``` localhost/datarig/profile ``` to conduct profile analysis by entering the twitter profile name without the@ and submit.
The output will be a table showcasing the ouput statistics eg the number of followers, tweets, retweets and favorites.

- Timeline Amalysis
Navigate to ``` localhost/datarig/timeline``` to conduct a timeline analysis. The timeline analysis looks at the most common words used 
by a user. here too you input the username without the @ and submit. The output will be a bar chart showcasing the most frequent words and their respective count

- Sentiment Analysis
Navigate to ``` localhost/datarig/timeline``` to conduct a sentiment analysis. Sentiment analysis looks at the reaction to tweets either positive negative or neutral. here you will input a keyword to conduct the analysis. The output will be a pie chart show casing the percentages of the sentiments





