# Robot-Process-Automation-1 : Mail , Attachment and Pdf automation using UiPath community version 2107.1.6498
![Uipath](https://github.com/atulkumarpccs/Robot-Process-Automation-1/blob/master/Images/Uipath_2.png)


 ### Requirement/Use Case :
 
![UiPath](https://github.com/atulkumarpccs/Robot-Process-Automation-1/blob/master/Images/Uipath_1.png)
 
 
 ```Business process handling through RPA```
As an input we should have an email with attached PDF form (in the attachment). The robot should read email, save attachment to any folder, open PDF and read following fields from pdf:

* 5 digit investor number (in the example it is 54325)
* Street Address
* Suburb
* State
* Postcode
* Country

Then robot should open Excel and enter this data into the file (file to be created by developer). 

 
 ### Setup Environment :
 * Install `Community adition`
 
   follows the link for windows
   
   <https://www.uipath.com/freetrial-or-community>
   
   
 * Please refer file ``videos,forum, installtion`` if any package is missing in UiPath on windows 10. 
   
 ### Build Steps :
 
 * After doing `installation` , please install other package realted to mail, pdf ...as per need .
 
 * Clone the project from github >>``git clone https://github.com/atulkumarpccs/Robot-Process-Automation-1.git `` 
 
 * Open the file in UiPath 
  
 ### Known Issues :
 
 * Set up is done for windows environment
 
 * Set is not done for other platform.
 
 * Some of package are installed manully in UiPath through ``UiPath Manager`` 
 
