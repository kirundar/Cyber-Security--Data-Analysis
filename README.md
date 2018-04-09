# Cyber-Security--Data-Analysis

Process Flow
																																																							
Step-by-step Process:
1.	Downloaded Data from http://csr.lanl.gov/data/cyber1/
2.	Adopted the sampling Strategy to handle 64 GB of data
3.	Detected, labelled and Corrected (or removed) corrupt or inaccurate records from a record set, table or database (if any)
4.	Summarized, Aggregated, and Grouped data in Python Pandas for data analysis. 
5.	Converted data into a graphical or visual representation using Tableau.	

Analysis:
1. Under the unknown Authentication data type ‘?’- There’s  high number of failed and successful attempts under that category.   Clearly the authentication strength should correlate to the value of the assets it is protecting but due to  the ‘Unknown’ category it can been that the data is more at risk of invasion.  It can be see that the authentication mechanism is weak, flawed or vulnerable.

2. NTLM, Kerberos, and Negotiate authentication are more secure forms of authentication because the user name and password are hashed before being sent across the network. When NTLM, Kerberos, or Negotiate authentication are enabled, the user's browser proves its knowledge of the password through a cryptographic exchange with your Forefront TMG server, involving hashing. 

Recommendation:
Authentication Bypass
The whole purpose of authentication is to ensure that only authorized users gain access to the application capabilities and the information it contains.  It is essential therefore that the system verifies the “authentication status” of the user for every user action or request before it is carried out. The ability of a user to access any application feature or resource without having first authenticated represents a Weak Authentication vulnerability.
