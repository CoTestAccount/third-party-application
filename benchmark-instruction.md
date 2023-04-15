## Excessive Permission Annotation Instructions

Below are the instructions we used for the manual annotations needed for the
benchmark labeling in the paper (Section [to be decided]).


### Instructions

Consider the following Google Third-Party app permission scope:

(Third-Party app must require permission from its host app for correct functionality.)

\<sample app with scope\>

--- 

Q1: Does this Third-Party app request more permission? 
    
- [ ] Yes 
- [ ] No

Q2: If the answer is Yes for Q1, could you list the excessive permissions? 

[a list of excessive permissions]

---

**Excessive Permission:** 

Example 1, a third-party application that functions as a mathematics editor for Google Spreadsheet:

permission 1: send email as you.                                          -> excessive

permission 2: edit your Google Spreadsheet that currently interacted with.-> no excessive

permission 3: edit all your Google Spreasheet.                            -> excessive


---

