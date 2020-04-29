# Google-Form-Validation-with-RE
Regular Expression for validating  e-mail ID and Indian mobile number specifically on Google forms.

In many of the personal or professional purposes we are usually designing Google form, to colelct import informations. In such cases it is very much obvious that we are not getting proper responses due to human entry level error or sometimes by intentions. 

Google form provides some features to manage this, like you can restrict user to not entering text in the field of mobile number or not allow them to enter number in the field of their name. But, these seems not enough to serve our purpose and to overcome we ccan use Regular expressions in Google form itself.

For Mobile number (Indian), considering as per guidlines till date numbers are starting with 6, 7, 8, or 9 and without +91 or 0.

Regular Expression is ^[789]\d{9}$

For e-mail IDs.

Regular Expression is (?:[a-z0-9!#$%&'*+/=?^_`{|}~-]+(?:\.[a-z0-9!#$%&'*+/=?^_`{|}~-]+)*|"(?:[\x01-\x08\x0b\x0c\x0e-\x1f\x21\x23-\x5b\x5d-\x7f]|\\[\x01-\x09\x0b\x0c\x0e-\x7f])*")@(?:(?:[a-z0-9](?:[a-z0-9-]*[a-z0-9])?\.)+[a-z0-9](?:[a-z0-9-]*[a-z0-9])?|\[(?:(?:(2(5[0-5]|[0-4][0-9])|1[0-9][0-9]|[1-9]?[0-9]))\.){3}(?:(2(5[0-5]|[0-4][0-9])|1[0-9][0-9]|[1-9]?[0-9])|[a-z0-9-]*[a-z0-9]:(?:[\x01-\x08\x0b\x0c\x0e-\x1f\x21-\x5a\x53-\x7f]|\\[\x01-\x09\x0b\x0c\x0e-\x7f])+)\])


If your are programmer then use can modify these regular expressions according to your needs, other can csimple copy and paste.
