## Excessive Permission Annotation Instructions

Below are the instructions we used for the manual annotations needed for the
benchmark labeling in the paper (Section VI).


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

**Functionality Permissions:**
Align with the problem definition in our paper, Functionality Permissions refer to the permissions that must be satisfied for the Third-party-application(TPA) to function correctly.

Example 1, a third-party application that functions as a mathematics editor for Google Spreadsheet:

permission 1: edit your Google Spreadsheet that currently interacted with. -> functionality permission

permission 2: see your Google Spreadsheet that currently interacted with.  -> functionality permission

reasons for permission 2: the TPA would convert your content (e.g. X_{i} + Y_{i} = X^{2}) to a image and that requires to read the content you are currently editing.



**Excessive Permissions:** 
Align with the problem definition in our paper, Excessive Permissions refer to the permissions that can be removed without affecting the functionality of Third-party-application(TPA).

Example 1, a third-party application that functions as a mathematics editor for Google Spreadsheet:

permission 1: send email as you.                                            -> excessive

permission 2: edit your Google Spreadsheet that currently interacted with.  -> no excessive

permission 3: edit all your Google Spreasheet.                              -> excessive

permission 4: delete your Google Spreadsheet that currently interacted with.-> excessive

permission 5: create your Google Spreadsheet that currently interacted with.-> excessive

permission 6: share your Google Spreadsheet that currently interacted with. -> excessive

---

