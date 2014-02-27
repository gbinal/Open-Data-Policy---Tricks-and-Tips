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
  4. theme
  5. language
  5. references
8. Have you confirmed that the following time-based fields are formatted correctly?  
  1. modified
  2. temporal
  3. issued
9. Have you confirmed that each identifier is unique and is set to remain consistent?  
10. Is each of the following fields represented only by approved values?  
  1. accessLevel
  2. dataQuality
  3. accrualPeriodicity



### The Long Tail
* 



## Loose Notes

Acceptable Redirects  (how to test?)  

   Impt. required if applicable fields (bureau code, program code, accessURL, accessLevelComment)  
Number of entries   

Formatting of keywords, references, theme, distribution, dataquality, ...  
contact name, email   
format  
bureau code  
program code   
accessLevelComment  
accessURL  
spatial formatting   
webservice  
language formatting   
accrualp usage  
landingpage URL usage  
theme  



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


