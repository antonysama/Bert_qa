This is customization of a popular python repo to do close domain q&a. I customized it do qo q&a on my own csv files. Which can be either short news articles or certain case law.

Constraints with the popular repo are that it doesn't work well with  custom data. It requires that column names be lowercase. And that "paragraphs" be a list with at least 3 elements. 

This customization works if the text has 3 or more sentences. It loads your file with "load_from_csv" method and includes nltk among  requirements.


Reference: https://github.com/cdqa-suite/cdQA
