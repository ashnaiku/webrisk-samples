# Web Risk Samples


## Description
This folder has projects to demostrate how to use different APIs of Web Risk in different languages 

## What is Web Risk
Web Risk is a Google Cloud service that lets client applications check URLs against Google's constantly updated lists of unsafe web resources. 


## APIs


- The Lookup API lets your client applications check if a URL is included on any of the Web Risk lists.

- The Update API lets your client applications download hashed versions of the Web Risk lists for storage in a local or in-memory database. URLs can then be checked locally. 

- The Web Risk's Extended Coverage API helps to improve the coverage of malicious urls with a small amount (less than 10%) of potential false positives.

- The Evaluate API to let your client applications evaluate the maliciousness of a URL. 

- The Submission URLs lets your submit the URL that you suspect are unsafe to Safe Browsing for analysis, and asynchronously check the results of these submissions. 



## How to install and run

git clone https://github.com/ashnaiku/webrisk-samples

cd webrisk-samples/
cd webrisk-python-01/

pip3 install -r requirements.txt 

python3 webrisk_cmd.py 

python3 app.py	
http://localhost:5000
