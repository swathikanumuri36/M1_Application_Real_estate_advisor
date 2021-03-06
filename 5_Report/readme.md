# Real-estate Advisor

# Requirements

<br>

# Introduction


- Real estate will provide facility to the user to search Residential and Commercial property and view property. It will also provide facility to view the property by admin and user.User will able to upload the property information to the site and able to manage it.<br>
- Real estate advisor helps people to connect ecah other for buying and selling of their properties.Buyers are one click away to get the information of all type of properties that are in and around them and sellers can register their properties by providing the specifications of their property.This makes real estate globalised.The traditional way of business takes more time but compare to real estate advisior time conflicts are decreased because the buyer and seller can access at any time.<br>

# Research

- Real estate is one of the major business which requires a high attention.while doing the research I found that mediators play a vital role in closing a deal.
Mediators take a huge amount of money on successful completion of a deal.To overcome this real estate advisor helps buyer to connect directly to the customer without any mediator. This decreases the burden to buyer and seller too.
- Time is also a barrier.In order to meet a person to view the property,the buyer's only source is mediator so it takes more time to view the property.

## Real-estste advisor has advantages ans a disadvantages too.

### Advantages

- 24/7 Accessability
- Time saving
- Save money
- No mediator
- Easy access

### Disadvantages

-There can be fraudsters who might keep fake information. So the two parties (Buyer and sellers ) need to be very particular in checking the proofs
<br>
<br>

# Cost and Features

- Real estate advisor has two features that is Buyer and Seller.

### Buyer:
- Can view the all records of available properties.
- Can view properties by the type of property.


### Seller:
- Can add their properties with specifications and other details like address,contact number,etc.
- Can modify the added details of the Properties.
- Delete the record of properties,incase property is sold out.

# SWOT Analysis

![Swot png](https://user-images.githubusercontent.com/94305490/143232086-9ff976f8-c781-470c-9466-a60e5101a77f.jpg)


## 4W and 1H

### WHO:
Everyone who has a desire to buy a property or a need to sell their property they can use it.

### WHAT:

A utility which can connect buyers and sellers where one can buy or sell their asserts or properties.
### WHEN:

Time is not a barrier, so it can be used at any point of time.
### WHERE:

As it is globalised, it can be used anywhere and all the asserts can viewed which in and out of the range.
### HOW:

Buyers can view all the properties or asserts availablle or can also view by the type of property,available by adding specifications and can also modify them.If the property is sold out,seller can remove that properties.

## Detail Requirements
<br>

### High Level Requirement

| ID | Description | Status |
| ----- | ----------------- | ----------- |
| HLR01 | Using sell option | Implemented |
| HLR02 | Using buy option | Implemented |

<br>
<br>

### Low Level Requirements:

| ID | Description | HLR_ID | Status |
| ----- | -------------------------------------------------------------------------------------------------------------------------- | ----------- | ----------- |
| LLR01 | Seller registers property | HLR01 | Implemented |
| LLR02 | Seller enters specifications of property like, type of property and area of it and also enters contact details and address | HLR01 | Implemented |
| LLR03 | Seller can modify the entered details if they were incorrect | HLR01 | Implemented |
| LLR04 | Sellers can remove their data if their property was sold out | HLR01 | Implemented |
| LLR05 | Buyers can view all the properties that are available | HLR02 | Implemented |
| LLR06 | Buyers can view the asserts by the type of assert they want to buy | HLR02 | Implemented |
| LLR07 | Buyers have an option to view how many **number** of properties are available to them | HLR02 | Implemented |
| LLR08 | Both buyers and sellers has an option to exit from the interface | HLR01 HLR02 | Implemented |



# Design

## Behavioural diagrams

### Activity diagram

![Diagram](https://user-images.githubusercontent.com/94305490/142737288-b08cc816-bc69-440e-8a0c-737342236d1c.png)


### use case diagram

![BEHAvioural dia](https://user-images.githubusercontent.com/94305490/142736278-87b76bbd-fc26-49ef-842f-299ccff54dd5.png)


## Structural diagram

### Class diagram

![structural diagram](https://user-images.githubusercontent.com/94305490/142732591-f49e2ee1-da21-40a5-9f4f-8c1df5b18d2d.png)


### Component diagram

![Highlevel Structal](https://user-images.githubusercontent.com/94305490/142728268-d91d2e74-fb4a-4093-9c11-aa5147153431.png)


# Implementation
## Introduction
This folder conatins all the coding files as well as the resources and testing files neede for proper execution of program
## Instructions to execute
1. Clone my repository
2. Go to 3_Implementation folder
3. Make sure your system meets all software and hardware requirements
4. Run "make run" command in terminal for main code execution
5. Run "make run_test" command in terminal for test code execution


| Folder | Description |
| --- | --- |
| inc | Contains header files |
| src | Contains additional source file for compilation |
| test | Contains unit testing files


# Test Plan
<br>

## High Level Test Plan
<br>

| ID | Description | Expected I/P | Expected O/P | Actual O/P | Type of Test |
|----|----------------------|-------------|-------------|-------------|--------------|
|HP01|Sellers UI | Character s| Enters to sellers page| Pass| Requirement |
|HP02| Buyers UI | Character b| Enters to buyers  page| Pass| Requirement|

<br>
<br>
<br>

## Low Level Test Plan
<br>

|ID| Description | Expected I/P | Expected O/P| Actual O/P | Type of Test|
|----|------------------------|---------------|--------------|---------------|---------------|
|LP01| Buyer viewing all the properties available| Integer 1| Views all properties and exits | Pass | Requirement|
|LP02| Buyer views by type of property| Integer 2| Views by type and asks to view another type| Pass| Requirement|
|LP03| Buyer has an option to exit| Integer 4|Exits |Pass| Requirement|
|LP04| Buyer can see total number of properties available| Integer 3|  2| 2| Requirement|
|LP05| Seller can register his property|Integer 1, Char name, Long int cmunber, Char ptype, int ext, char place, char country|Exits after entering details|Pass|Requirement|
|LP06| Seller can register another property|char y| Opens register module|Pass| Requirement|
|LP07|Seller can delete property| char name|Delete from file| Pass |Requirement|
|LP08| Seller can update if there are errors while entering information| Char name|Opens modify module| Pass| Requirement|
|LP09|seller can update another |char y|Modifies another information|Pass| Requirement|
|LP10|Seller can exit|Integer 4| Exits from module|Pass|Requirement|


