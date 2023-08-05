# SwaggerPetstore_Rest_API_Newman

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
- https://documenter.getpostman.com/view/26899722/2s9XxyRYjq

## Test case list:
## User
1. ### Create a user
	> Create Data Sets Using the Dynamic Random Variables.
	1. > Successful message
	2. > Response Code
	3. > Response type
	4. > Response message
	5. > Response Time below 350
   
2. ### Get a user
	1. > User ID
        2. > User name
	3. > First name
	4. > Last name
	5. > Email
	6. > Phone
	7. > User Status
	8. > Response Time below 350
3. ### Update a user
	1. > Successful message
	2. > Response Code
	3. > Response type
	4. > Response message
	5. > Response Time below 350
4. ### Get a user after Update
	1. > User ID
    	2. > User name
	3. > First name
	4. > Last name
	5. > Email
	6. > Phone
	7. > User Status
	8. > Response Time below 350
5. ### Delete a user
	1. > Successful message
	2. > Response Code
	3. > Response type
	4. > Response message
	5. > Response Time below 350
6. ### Get a user after Delete
	1. > Not found
	2. > Response Code
	3. > Response type
	4. > Response message
	5. > Response Time below 350
7. ### User Login
	1. > Successful message
    	2. > Response Code
	3. > Response type
	4. > Response message
	5. > Response Time below 350
8. ### User Logout
	1. > Successful message
    	2. > Response Code
	3. > Response type
	4. > Response message
	5. > Response Time below 350
9. ### Create List of users with Array
	1. > Successful message
    	2. > Response Code
	3. > Response type
	4. > Response message
	5. > Response Time below 350
10. ### Get a User from Array
	1. > User ID
    	2. > User name
	3. > First name
	4. > Last name
	5. > Email
	6. > Phone
	7. > User Status
	8. > Response Time below 350
## Pet
## Store

## Newman Report Summary:
![Newman Report Summary](https://github.com/ManikHossain27/SwaggerPetstore/assets/131261253/a44582b5-0d75-4070-9a73-bb770e00358b)

![Newman Report Summary](https://github.com/ManikHossain27/SwaggerPetstore/assets/131261253/7cbdf3d8-5f74-4060-8a34-a099f05735db)

![Newman Report Summary](https://github.com/ManikHossain27/SwaggerPetstore/assets/131261253/26b3015c-698b-4f16-af00-531ffed523c8)


