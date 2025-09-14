# HW1 - Web Science Intro
### Bryson Coons
### CS 432, Fall 2025
### September 14, 2025

# Q1
For this question, I began by analyzing which of the sites linked together within themselves to find the SCC sites. Then from there, I analyzed how the remaining sites linked related to the SCC. From there, I was able to begin constructing a directed graph, beginning with the SCC, and could move letters around as necessary. I was then able to determine which sites served as which "parts" of their ecosystem.

SCC - A B C D G
IN - F M
OUT - L H
Tendril - E (serves an IN tendril)
Tube - O J N (connects between IN and OUT)
Disconnected - K I (serves as its own little ecosystem)

The figure below shows my directed graph.

![Q1 Directed Graph](20250914_180019.jpg)

*If you want to include code in your report, you can insert a screenshot (if it's legible), or you can copy/paste the code into a fenced code block.*

```python
#!/usr/local/bin/python3
# testargs.py

import sys

print ("{} is the name of the script." . format(sys.argv[0]))
print ("There are {} arguments: {}" . format(len(sys.argv), str(sys.argv)))

for ind, arg in enumerate(sys.argv):
    print ("[{}]: {} {}".format(ind,arg,sys.argv[ind]))
```

The table below shows a simple table.  

|Week|Date|Topic|
|:---|:---|:---|
|1|Sep 1, 3|Introduction, What's Vis and Why Do It?|
|2|Sep 8, 10|Data and Data Cleaning|
|3|Sep 15, 17|Marks and Channels|

The table below shows an example confusion matrix (you'll see this term later) from <https://en.wikipedia.org/wiki/Confusion_matrix>.

| | |Actual||
|---|---|---|---|
|**Predicted**| |Cat|Dog|
| |Cat|5 (TP)|3 (FP)|
| |Dog|2 (FN)|3 (TN)|

*You must provide some discussion of every answer. Discuss how you arrived at the answer and the tools you used. Discuss the implications of your answer.*

# Q2

## Answer

# Q3

## Answer

# References

*Every report must list the references that you consulted while completing the assignment. If you consulted a webpage, you must include the URL.  These are just a couple examples.*

* Stack Overflow, How can I parse (read) and use JSON in Python?, <https://stackoverflow.com/questions/7771011/how-can-i-parse-read-and-use-json-in-python>
* ChatGPT conversation, Initial prompt: "write a python line to detect if a string ends with .png", <https://chat.openai.com/share/5de76e93-c26b-4665-a0fc-b782b01a9285>
