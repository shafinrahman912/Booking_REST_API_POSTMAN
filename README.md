# Booking_REST_API_POSTMAN

## How to run this project
- Clone this project
- Open with Postman / Command Shell
- Run Command:  
```console 
newman run StudentDetails.postman_collection.json -e StudentDetails.postman_environment.json 
```
- Run Command for Report: 
```console 
newman run StudentDetails.postman_collection.json -e StudentDetails.postman_environment.json -r cli,htmlextra
```

## Technology used:
- Postman
- Newman

## Prerequisite:
- Jdk
- Node Js
- Newman
- Html Report Library

## Newman and Report Installation Process:
- Newman Install Command:
```console
npm install -g newman-reporter-htmlextra
```
- Newman Html Report Install Command:
```console
npm install -g newman-reporter-htmlextra
```

## API Documentation:
- https://documenter.getpostman.com/view/28551467/2s9XxwvtRM

## Test case list:
1. ### Create Booking
	> Create Data Sets Using the Dynamic Random Variables and validation of status code in the test case.
	1. > Validating Status Code
2. ### Verify Created Booking Details
	> Validation of the following field values in the test case :
   	1. > Validating Status Code
    2. > Validating First Name
 	  3. > Validating Last Name
   	4. > Validating Total Price
   	5. > Validating Deposit Paid
    6. > Validating Checkin Date
    7. > Validating Checkout Date
    8. > Validating Additional Needs

3. ### Create Authentication Token
	> Create Authentication Token Data Using User Name and User Password
 
4. ### Update Booking
   > Set Pregenerated Authentication Token in Update Request Headers Using the Dynamic Variables.
   
   > Update Data Sets Using the Dynamic Random Variables and validation of status code in the test case.
    1. > Validating Status Code
    
5. ### Verify Updated Booking
	> Validation of the following field values in the test case :
 	  1. > Validating Status Code
    2. > Validating First Name
 	  3. > Validating Last Name
 	  4. > Validating Total Price
 	  5. > Validating Deposit Paid
    6. > Validating Checkin Date
    7. > Validating Checkout Date
    8. > Validating Additional Needs

6.  ### Delete Specific Booking
	> Validation of status code in the test case :
	  1. > Validating Status Code
  

## Newman Report Summary:
![Newman Report Summary](https://github.com/shafinrahman912/Booking_REST_API_POSTMAN/assets/83553368/fc92ec62-99ee-4621-8ee7-74e891c28ad2)

![Newman Report Summary](https://github.com/shafinrahman912/Booking_REST_API_POSTMAN/assets/83553368/fd72ea6a-81cf-42c4-9710-37b5b9c76b8c)

![Newman Report Summary](https://github.com/shafinrahman912/Booking_REST_API_POSTMAN/assets/83553368/cbd3c989-db65-4358-aee2-e2f68cc59010)


