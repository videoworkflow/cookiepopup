Anonymised repository for reviews
It contains the data collected for the study of GDPR consent.

Description of data 

## Raw Data
Screenshots and raw data of each indivial website visited.
Each website data is sepearted in each folder (field 2 of coded data)
Each folder consits of the follwing information
* Screenshots(s) - folder containing screenshots of all cookie consent related interfaces
* Cookies - a document containg all cookies information if it is made available on the website
* Text of the consent requirement - The entire page which lists the cookie policy of the website
   

## Coded Data
Tabular data with the following fields in this order
1. Link - the site link used in the data collection
2. Key to Folder - the folder which stores the raw data collected (read Raw Data sections for organization of this folder)
3. Type - news website or magazine website
4. Country - If it is global website it is the country where the news site headquarter is
5. "not yes option - Is there an option or a way for the visitor to deny the cookie consent
6. Name of "not yes"option - The text on the link that allows the users to customize/deny the cookie consent
7. "not yes"option same UI element level as "yes" - if not then there is a information (button, link, link next to button, check boxes, drop down menu)
8. Location of pop-up box - where is the pop up box located on a deskop view
9. Content scrollable while privacy widget is active - whether the content is still accessible while pop up is active. (scrollable, grayed out)
10. Number of words on the "options page" = the number of worlds on the page when there is no "deny all" option but requires to visit another page to customize/deny consent
11. Number of clicks until "not-yes" option - Number of clicks reuiqred to opt out all possible cookies and return to access the page
12. Immediate visibilty of "not yes" option - Whether not yes option is instantly visible without scrolling down or requires scrolling down to click "not yes" option
13. Clarity of options - How easy it is to understand how to manage cookie consent and adjust it
14. What are cookeis used and their functions. If yes then is it informative - Does the cookie widget list what types of cookies are used and what are their functions. If listed then if it is easier to understand
15. Is third-party consent handling is used - If the website uses a third-party consent handling service. If yes which third-party consent is used. (Additional information about third-party handler is present in the raw data folder)
16. Is the website still accessible after total opt-out -  If the website is still usable after the users opt out from all possible cookies or in some cases whether some functionalities are removed such as pictures or videos 
17. Is dark pattern used - which type of dark patterns are present in the document
18. "Are you sure" message at the end of the opt-out process - Some websites asks for reconfirmation after all cookie consents has been opted out. This field contains the messages showed in this reconfirmation and screenshots of these are available in the raw data folder
