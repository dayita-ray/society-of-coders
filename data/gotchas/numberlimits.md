title: 'Number limits'
date: '06-16-2021'
class: 'CSP' # CSA or CSP
section: 1 # A number to represent Unit or Big Idea (optional for pbl)
keywords: 'overflow, roundoff' # Keywords to describe your project seperated by commas
tech: 'binary, error' # What you used (Language, frameworks, Database) seperated by commas (only for pbl)
author: 'Dayita Ray' # Optional
authorLink: 'https://github.com/dayita-ray' # Optional 
---

Overflow: The computer cannot handle the largest integer above a certain number of digits
Ex: Overflow is where 0.2+0.2 may become 0.400005 
Roundoff: Repeating digits end somewhere because they cannot continue in binary together so they create an error
Ex: If the maximum is 4 binary digits (2x where x is 4), the function cannot surpass 16

Practice Problem
Which will result in a roundoff error with 5 binary digits? 31+1 or 31*1

Answer: 31+1 because it is 32 and the answer cannot be above 25=32
