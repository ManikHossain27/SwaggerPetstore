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
	5. > Response Time below 350ms
   
2. ### Get a user
	1. > User ID
	2. > User name
	3. > First name
	4. > Last name
	5. > Email
	6. > Phone
	7. > User Status
	8. > Response Time below 350ms
3. ### Update a user
	1. > Successful message
	2. > Response Code
	3. > Response type
	4. > Response message
	5. > Response Time below 350ms
4. ### Get a user after Update
	1. > User ID
	2. > User name
	3. > First name
	4. > Last name
	5. > Email
	6. > Phone
	7. > User Status
	8. > Response Time below 350ms
5. ### Delete a user
	1. > Successful message
	2. > Response Code
	3. > Response type
	4. > Response message
	5. > Response Time below 350ms
6. ### Get a user after Delete
	1. > Not found
	2. > Response Code
	3. > Response type
	4. > Response message
	5. > Response Time below 350ms
7. ### User Login
	1. > Successful message
	2. > Response Code
	3. > Response type
	4. > Response message
	5. > Response Time below 350ms
8. ### User Logout
	1. > Successful message
	2. > Response Code
	3. > Response type
	4. > Response message
	5. > Response Time below 350ms
9. ### Create List of users with Array
	1. > Successful message
	2. > Response Code
	3. > Response type
	4. > Response message
	5. > Response Time below 350ms
10. ### Get a User from Array
	1. > User ID
	2. > User name
	3. > First name
	4. > Last name
	5. > Email
	6. > Phone
	7. > User Status
	8. > Response Time below 350ms

## Pet
1. ## Add a new pet to the store
	1. > Successful message
	2. > Response Time below 350ms
2. ## Find Pet by ID
	1. > Pet ID
	2. > Category ID
	3. > Category name
	4. > Pet name
	5. > PhotoUrls
	6. > Tags id
	7. > Tags name
	8. > Atatus
	9. > Response Time below 350ms
3. ## Update an existing pet
	1. > Successful message
	2. > Response Time below 350ms
4. ## Find pet after Update
	1. > Pet ID
	2. > Category ID
	3. > Category name
	4. > Pet name
	5. > PhotoUrls
	6. > Tags id
	7. > Tags name
	8. > Atatus
	9. > Response Time below 350ms
5. ## Upload an image
	1. > Successful message
	2. > Response Code
	3. > Response type
	4. > Response message
	5. > Response Time below 350ms
6. ## Find Pets bt status
	1. > Status 'available'
	2. > Response Time below 350ms
7. ## Update a pet in the store with form-data
	1. > Successful message
	2. > Response Code
	3. > Response type
	4. > Response message
	5. > Response Time below 350ms
8. ## Find pet after update
	1. > Pet ID
	2. > Category ID
	3. > Category name
	4. > Pet name
	5. > PhotoUrls
	6. > Tags id
	7. > Tags name
	8. > Atatus
	9. > Response Time below 350ms
9. ## Delete pet
	1. > Successful message
	2. > Response Code
	3. > Response type
	4. > Response message
	5. > Response Time below 350ms
## Store
1. ## Add a new pet to the store
	1. > Successful message
	2. > Response Time below 350ms
2. ## Find Pet by ID
	1. > Order ID
	2. > Quantity
	3. > Ship Date
	4. > Status
	5. > Complete
	6. > Response Time below 350ms
3. ## Update an existing pet
	1. > Successful message
	2. > Response Code
	3. > Response type
	4. > Response message
	5. > Response Time below 350ms
4. ## Find pet after Update
	1. > Sold
	2. > String
	3. > Unavailable
	4. > Pending
	5. > Available
	6. > Response Time below 350ms


## Newman Report Summary:
![Newman Report Summary](https://github.com/ManikHossain27/SwaggerPetstore/assets/131261253/a44582b5-0d75-4070-9a73-bb770e00358b)

![Newman Report Summary](https://github.com/ManikHossain27/SwaggerPetstore/assets/131261253/7cbdf3d8-5f74-4060-8a34-a099f05735db)

![Newman Report Summary](https://github.com/ManikHossain27/SwaggerPetstore/assets/131261253/26b3015c-698b-4f16-af00-531ffed523c8)


