

## How to go from Inventory.Data.gov to your Public Data Listing 

* Navigate to your organization in inventory.data.gov.  
* Admins should see a button that says Public Data Listing:

![image](https://f.cloud.github.com/assets/633088/2399964/a45f1652-aa04-11e3-9d7d-8574382fe9a6.png)

* After clicking that button, a zip folder named pdl.zip should download to your desktop.  Open it.  
* You will then see one or two files, named datajson.txt or errorlog.txt.  

![image](https://f.cloud.github.com/assets/633088/2399991/01a9459e-aa05-11e3-8084-cf4e18b8658d.png)
 * Datajson.txt is your catalog material - it contains each of your records that passed validation.  If it is not present, then none of your records are validating successfully and you should consult the error log.  
 * Errorlog.txt is your error report, that will help to identify which records are not validating and why.  If it is not present, each of your records validated successfully and are included in your datajson.txt file.  
 * If both files are present, then some of the records are validating successfully and are contained in the datajson.txt file, while the rest did not and are discussed in the error report.  
 * Your goal should be to edit any invalid entries until you are receiving a datajson.txt file and not receiving an errorlog.txt file.  At that point, continue with the below.  

* You now want to rename your datajson.txt file to data.json.  You can do this either by opening it in a text editor and resaving as data.json or by renaming the file in your file manager.  

![image](https://f.cloud.github.com/assets/633088/2400147/f2646f30-aa06-11e3-88a7-9b057bfa1647.png)

* Once you end up with a file named data.json that contains the contents of your datajson.txt file, host it at www.agency.gov/data.json.  
