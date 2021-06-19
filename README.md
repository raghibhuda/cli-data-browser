# Make a command line tool to browse a json file

**Make sure the code is well commented and have a nice documentation**


---


Given this source: [Sample JSON](sample_user_data.json)


```json
[
 {
        "_id": "60cdc5465c2acc72b9cea648",
        "isActive": true,
        "balance": "$2,221.59",
        "picture": "http://placehold.it/32x32",
        "age": 37,
        "eyeColor": "green",
        "name": "Victoria Parker",
        "gender": "female",
        "company": "SENSATE",
        "email": "victoriaparker@sensate.com",
        "phone": "+1 (905) 570-3791",
        "address": {
            "street": "914 Green Street",
            "city": "Nettie",
            "state": "Virginia",
            "latitude": 73.566683,
            "longitude": 165.268235
        },
        "about": "Labore Lorem duis in exercitation est nostrud consectetur ...",
        "registered": "2020-01-21T11:07:45 -06:00",
        "tags": [
            "excepteur",
            "tempor",
            "non",
            "qui",
            "irure",
            "exercitation",
            "velit"
        ],
        "friends": [
            {
                "id": 0,
                "name": "Violet Watts"
            },
            {
                "id": 1,
                "name": "Pauline Saunders"
            },
            {
                "id": 2,
                "name": "Guadalupe Daniel"
            }
        ],
        "greeting": "Hello, Victoria Parker! You have 29 unread messages.",
        "favoriteFruit": "banana"
    },
    .............
]
```



# What you have to do 
You have to make a command line tool that will take some arguments as some questions. 
Then you have to browse the sample json data to get the answers . 

First question will be like this 
```
    Do you want to know who is the richest man on the list (y/n) : [Pressed y]
    Output: 
        Name: Victoria Parker
        Address: 914 Green Street,Nettie,Virginia
        Balance : $2,221.59
```
Second will be like this :
```
   Are you interested in men ,woman or both  ? (m/f/b/n) : Pressed[f]
   Give a range of your friend's preffered age (Ex: 20-30): [Input 20-45]
   Output:
        Name: Victoria Parker
        Phone: +1 (905) 570-3791
        Sex: Female,
        Age: 37,
        Address: Nettie

        Name: Casandra Carr
        Phone: +1 (939) 567-2504
        Sex: Female
        Age: 38,
        Address: Edinburg
```
Conditions on second query:
    
 - You have to get the preferred gender parameter from command prompt and search on the basis of this . 
 - Notice that the people who have less than five friends are allowed to show on the result or willing to be friend. 
 - On the other hand ,you have to search according to the age range that is given. 
 - In result , you have to show the city name as his/her address.
 
   
    
Instructions
- Proper validation should be added while getting input from command prompt
- In general user can skip any question by pressing [n] . This scenario should be handled also
- Optimize for speed/performance
- Remove as many loops as possible
- Remove duplicate functions
- Keep it modular, functions should be in different files if needed
- Make it readable
  - Explain **why** in the comments
  - Don’t write comments that we don’t need
  
## Submit the solution like this:
- Clone this repo or download the json file 
- Make a public or private repo and push the code there . Add me `raghibhuda@gamil.com` as a collaborator there.
- Add a read me file and describe how to run it locally and provide some working screenshots
- Cheers !