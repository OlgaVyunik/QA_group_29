## 1. ID
Identifier is a unique value to distinguish one defect report from another, and is used in all kinds of references.   
## 2. Summary
Summary should answer three questions (“What happened?” “Where did it happen?” “Under what circumstances did it happen?”) as succinctly as possible.
## 3. Description
Description provides detailed information on the defect and (mandatory) a description of the actual result, the expected result and a reference to the requirement (if
possible).
## 4. Steps to reproduce 
STR describe the actions to be taken to reproduce the defect.
## 5. Reproducibility
It shows whether the defect can be caused every time you go through the steps to reproduce.
- always
- sometimes
## 6. Severity
Severity shows the degree of damage to the project caused by the existence of the defect.
- **Critical** — the existence of a defect leads to catastrophic consequences on a large scale, for example: loss of data, disclosure of confidential information, disruption of key application functionality, etc.
- **Major** — defects cause significant inconvenience to many users in their typical activities, for example: clipboard inaccessibility, common keyboard shortcuts do not work, application has to be restarted when performing typical work scenarios.
- **Medium** — the existence of defect has little effect on typical user work scenarios, and/or there is a workaround to achieve the goal, for example: a dialog box does not close automatically after pressing “OK”/“Cancel” buttons, when printing several documents in a row the value of “Duplex printing” field value is not saved, sorting directions of a table field are mixed up.
- **Minor** — the existence of a defect is rarely detected by a small percentage of users and (almost) does not affect their work, for example: a typo in a deeply nested menu item, some window at once is displayed awkwardly (one needs to drag it to a convenient place), inaccurately displayed time to complete copying operations files.
## 7. Priority
Priority indicates how quickly the defect must be fixed.
- **ASAP (as soon as possible)** — indicates the need to fix the defect as quickly as possible. Depending on the context, “as soon as possible” can range from “in the nearest build” to minutes.
- **High** — the defect should be fixed out of turn, as it is either already objectively disruptive or will become so in the near future.
- **Normal** — the defect has to be fixed in the general order of priority. Most defects have this “Priority” field value.
- **Low** — fixing this defect will not have a significant impact on product quality in the foreseeable future.
## 8. Workaround
Workaround indicates whether there is an alternative workflow which would allow the user to achieve the goal. This field may simply take the values “Yes” and “No”.
## 9. Comment
Additional info can contain any data useful for understanding and fixing the defect.
## 10. Attachments
Screenshots, files that causes problems.