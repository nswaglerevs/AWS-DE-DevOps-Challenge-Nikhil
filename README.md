# AWS-DE-DevOps-Challenge-Nikhil
I have performed following steps which are given below
a) I have created an AWS CloudFormation template in which firstly created an AWS IAM Policy, then created a Lambda function, created a s3 Bucket and its s3 managed policy.
b) I have read and analysed the insights from the dataset  and found out that the data is seperated by delimeter which is ";". As the code needed to reusable i planned of creating dictionary and functions for cleaning the dataset so that it can be called anytime and can be reused for similiar dataset.

# Approach
#Cloudformation template
1. Cloudformation: I created a  iam role in which i have given s3 full policy. then i have successfully created Lambda function in which i have mentioned that i will be using python file by the name of index.py. So the challenge code should be implemented in index.py.
2. Python File: As mentioned above, the data was devided by delimeter which was ";". I that Takes inputs: header(string) and separator(string). Captures the required columns information,such as, their indexes. Splits the string on occurence of separator in the string, with exception when separator is in between double quotations(""). This method is used to clean the data correctly, mapping data to the right columns in cases when data has separator(';') in a single column. Now i planned to create states dictionary whoch is a dictionary with states as key and count as value. This function updates the dictionary with state and its number of certified applications.Same goes with the occupation. 
As the content was needed in descending order i planned of sorting using key pair method.

#Challenges faced
1. Using pandas the cleaning is much easier but without using pandas to finish code was bit difficult. 
1. I am good at  AWSservices, understanding of devOps and its tools, Cloudformation template. I faced problem to bring the python output to desired format. That the reason i could not follow up with the code further after sorting the output.

#Things i learned from this project
1. Got more hands-on practice at AWS cloudformation, writing a python code without using Pandas.
2. I upgraded  myself in problem solving methodology. Faced problems but could tackle and tried to atleast complete the project. It was tough to code without using pandas but managed somehow to achieve few things from the desired output.
