UVU PURL CAMPAIGN LOGIC SUMMARY - Landing Page

If STATE is EQUAL to Alaska, Arizona, California, Colorado, Hawaii, Idaho, Montana, Nevada, New Mexico, North Dakota, Oregon, South Dakota, Washington, Wyoming, Guam OR North Mariana Islands:
•	IF GPA is Less Than or Equal to (<=) 3.299 OR Test Score is Less Than or Equal to <= 23 (ACT) / 1179 (SAT) 
o	Direct to notQualifiedPopup.aspx

•	ELSE IF GPA is Greater Than (>) 3.299 AND Less Than or Equal to (<=) 3.699 AND Test Score is Greater Than (>) 23 (ACT) / 1179 (SAT) AND Less Than or Equal to (<=) 36 (ACT) / 1600 (SAT)
o	Direct to outreachPopup.aspx

•	ELSE IF GPA is Greater Than (>) 3.699 AND Less Than or Equal to (<=) 4.000 AND Test Score is Greater Than (>) 29 (ACT) / 1399 (SAT) AND Less Than or Equal to (<=) 36 (ACT) / 1600 (SAT)
o	Direct to Merit.aspx

•	ELSE Alert "Please ensure you have entered the correct values in each field."

If STATE is NOT EQUAL to Alaska, Arizona, California, Colorado, Hawaii, Idaho, Montana, Nevada, New Mexico, North Dakota, Oregon, South Dakota, Washington, Wyoming, Guam OR North Mariana Islands:
•	IF GPA is Less Than or Equal to (<=) 3.699 OR Test Score is Less Than or Equal to <= 29 (ACT) / 1399 (SAT) 
o	Direct to notQualifiedPopup.aspx

•	ELSE IF GPA is Greater Than (>) 3.699 AND Less Than or Equal to (<=) 4.000 AND Test Score is Greater Than (>) 29 (ACT) / 1399 (SAT) AND Less Than or Equal to (<=) 36 (ACT) / 1600 (SAT)
o	Direct to Merit.aspx

•	ELSE Alert "Please ensure you have entered the correct values in each field."

