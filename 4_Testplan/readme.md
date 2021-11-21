# Test Plan
<br>
## High Level Test Plan
<br>
| ID | Description | Expected I/P | Expected O/P                | Actual O/P   | Type of Test |<br>
|----|-------------|------------- |---------------------------- |------------- |--------------|<br>
|HP01|Sellers UI   | Character s  | Enters to sellers page      |   Pass       |Requirement   |<br>
|HP02| Buyers UI   | Character b  | Enters to buyers page       |   Pass       |Requirement   |<br>
<br>
<br>
<br>
## Low Level Test Plan
<br>
|ID| Description | Expected I/P | Expected O/P| Actual O/P | Type of Test|<br>
|----|------------------------|---------------|--------------|---------------|---------------|<br>
|LP01| Buyer viewing all the properties available| Integer 1| Views all properties and exits | Pass | Requirement|<br>
|LP02| Buyer views by type of property| Integer 2| Views by type and asks to view another type| Pass| Requirement|<br>
|LP03| Buyer has an option to exit| Integer 4|Exits |Pass| Requirement|<br>
|LP04| Buyer can see total number of properties available| Integer 3| 2| 2| Requirement|<br>
|LP05| Seller can register his property|Integer 1, Char name, Long int cmunber, Char ptype, int ext, char place, char country|Exits after entering details|Pass|Requirement|<br>
|LP06| Seller can register another property|char y| Opens register module|Pass| Requirement|<br>
|LP07|Seller can remove property| char name|Removes from file| Pass |Requirement|<br>
|LP08| Seller can modify if there are errors while entering information| Char name|Opens modify module| Pass| Requirement|<br>
|LP09|seller can modify another |char y|Modifies another information|Pass| Requirement|<br>
|LP07|Seller can delete property| char name|Delete from file| Pass |Requirement|<br>
|LP08| Seller can update if there are errors while entering information| Char name|Opens modify module| Pass| Requirement|<br>
|LP09|seller can update another |char y|Modifies another information|Pass| Requirement|<br>
|LP10|Seller can exit|Integer 4| Exits from module|Pass|Requirement|<br>

