1. Does www.agency.gov/data.json resolve?  
2. Does the file contain valid json?  
3. Does every entry include each of the following fields and are they populated?
  4. title
  5. description
  6. keyword
  7. modified
  8. publisher
  9. contactPoint
  10. mbox
  11. identifier
  12. accessLevel
  13. bureauCode
  14. programCode
6. Are any fields empty?  If so, they should contain `null` or be removed from that record. 
7. Are each of the following fields formatted as an array of strings? 
  1. keyword
  2. bureauCode
  3. programCode
8. Have you confirmed that the following time-based fields are formatted correctly?  
9. 
  






## Old Notes


URL works   
Acceptable Redirects  (how to test?)  
Valid JSON  
Correct Schema   
Required Fields  
   Impt. required if applicable fields (bureau code, program code, accessURL, accessLevelComment)  
Number of entries   
Metadata specific   
  
Formatting of keywords, references, theme, distribution, dataquality, ...  
contact name, email   
unique identifiers   
format  
bureau code  
program code   
accessLevelComment  
accessURL  
temporal/issued/modified formatting   
spatial formatting   
webservice  
language formatting   
accrualp usage  
landingpage URL usage  
theme  

Ensure brackets around:  
bureaucode  
programcode  
distribution  
keyword  
language   
references   
theme   


