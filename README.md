# MindsProject
## There are a few points I would like to mention:
## 1. I tried to scrape the reviews from the aljazeera website using BeautifulSoup and Selenium, but faced some issues to get the reviews together in a json file so instead I manually collected the reviews and pasted them into to text files. I created two folders : "data" and "data_copy" where "data" folder contains the original reviews and all modifications are done on the files in the "data_copy" folder.
## 2. First I performed an operation to remove all the punctuation marks, special characters, numbers, etc. Then I removed all the stop words from the text using the "gensim" library.
## 3. Next I used the "TextBlob" library to esimate the value of the sentiment from the text.
## 4. I made use of the "Plotyly" library to plot the values in a bar graph for every file in the folder.

## How to run the project:
### 1. Install jupyter notebook first using the command "pip3 install notebook"
### 2. Navigate to the repository directory using the command prompt and start the jupyter notebook using the command "jupyter notebook"
### 3. Now a window opens, select the file Minds summer programming challenge and in the menu bar click on the "Run" button and run all the cells one by one

