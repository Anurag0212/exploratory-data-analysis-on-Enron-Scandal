# Analysis on Enron Scandal

## Data Collection and Processing:  
The enron data-set is available at [CMU Enron data 1.82 GB tgz file](https://www.cs.cmu.edu/~./enron/enron_mail_20150507.tgz).  

You can download it manualy and unzip it or use below command: 

    $ curl -O https://www.cs.cmu.edu/~./enron/enron_mail_20150507.tgz  
 _Raw data is not uploaded in this repository because of it's size_

## Data Storing: 
Parsed the emails using email.parser library and created a folder structure in 'Month-Year' format.
for example, Mails which are sent on Jan 1999 is stored in the folder named - '01-1999'.  

## Libraries:  

    Email, email.parser, os, requests, json, re, datetime, shutil
    matplotlib.pyplot, pylab, nltk.corpus

## Analysis 1:
It is well known fact that CEO Jeﬀrey Skilling and Chairman Kenneth Lay of Enron at the time of the scandal, were holding regular meeting with their top executives to pressure them into ﬁnding new ways to hide Enron’s debt.  

Graph shows the same result, count of email containing meeting related words are highest between the period Jan 2001 to Oct 2001. Enron declared bankruptcy in Dec 2001 after that the count of meeting related words decreased significantly. 

<img width="751" alt="Trend Analysis of emails" src="https://github.com/Anurag0212/exploratory-data-analysis-on-Enron-Scandal/blob/master/analysis_1.PNG">


## Analysis 2:  
Extracted data by parsing the emails and created a text file containing the keywords which are under scrutiny and folder also contains the list of employees those were involved in discussion of deceitful act. 
Folder: [Emails with keywords](https://github.com/Anurag0212/exploratory-data-analysis-on-Enron-Scandal/tree/master/Emails%20with%20Keywords)
  

## Analysis 3:  
Keywords like ‘Gift’ and ‘Rewards’ were significantly increased by 76% in the email content in year 2001 as compared to 1999
<img width="751" src="https://github.com/Anurag0212/exploratory-data-analysis-on-Enron-Scandal/blob/master/Analysis_3.PNG">




