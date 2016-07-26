#WP Auto Brute
Auto enumerate WordPress users and run brute force attack!
##Description
WP Auto Brute is a tool that serves to Brute-Force attack automatically against enumerated users. This tool works by enumerate username based format **/author?=[ID]**.

To brute-force based on enumerated username, i use [WordPress Brute Force](https://github.com/claudioviviani/wordbrutepress) script by Claudio Viviani which have been combined in this tool. 
##Requirement
`pip install httplib2`

`pip install beautifulsoup4`

##How to Run
`wpbrute.py [-h] [-v] -u url.txt -l list.txt`

**-u** : File that contains URL list

**-l** : Password list

**-h** : help

**-v** : Version

**Example :**

`wpbrute.py -u url.txt -l list.txt`

**Note : This tool still in the process of development, you can help me to develop this tool.**

