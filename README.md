# Indian_SC_Judgment_database

This Repository Contains three files: 
(1) final_judge_database.csv - It contains more than 5000 Supreme Court Judgments from the years 1980-1990 that have the following columns: Case Title; Case Date; Judges Name(s); Issues; Decision (0 = dismissed; 1 = allowed); Cited Cases (Cases that are cited by the judge him/herself are scored higher (1.0) while cases that are cited by the lower court or advocates are scored lower (0.8))

(2) kannon_link_parser.ipynb - Is a python file that crawls indiankanoon.org website and collects links for the purpose of storing and scraping them.

(3) kanoon_scraper.ipynb - Is a python file that create the final_judge_database.csv and takes the links from kanoon_link_parser.ipynb and srapes the relevant data from them.

For any queries or comments, please contact me through email: noelshallum@gmail.com
