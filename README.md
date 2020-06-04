
# vue-webpack-minimalist
A minimal boilerplate for Vue and webpack with demo data to get up and running in no time.

**Getting Started**

- To get started, you need to have npm and node installed. 
- To install all dependencies for the dev environment simply run *'npm install'.* 
- You can start the webpack dev server using the *'npm start'* command. The server should hot-reload on code changes. 
- If you just want to build the files using webpack, you can use *'npm run webpack'.*


**API**

This is to demonstrate how you can using *get request*  to fetch the data.json file in the repository

GET: /data/:id

- call this endpoint to get the data for each chart
- <id> is an integer from 0-5

Example output: 

        {
        "_id": "5ed86a905f4e8d74618658b7",
        "index": 0,
        "guid": "5de569d4-4e3d-4967-8198-e9e3149a1ac7",
        "isActive": true,
        "balance": "$2,035.58",
        "picture": "http://placehold.it/32x32",
        "age": 32,
        "eyeColor": "brown",
        "name": "James Macdonald",
        "gender": "female",
        "company": "TRIPSCH",
        "email": "jamesmacdonald@tripsch.com",
        "phone": "+1 (923) 516-2070",
        "address": "665 Mayfair Drive, Fontanelle, Louisiana, 9986",
        "about": "Non dolor do adipisicing ex sit eu labore nulla. Ex voluptate qui incididunt irure officia cillum irure aute mollit mollit fugiat. Do ea occaecat adipisicing ipsum voluptate sint nulla nulla. Mollit magna velit enim Lorem ex excepteur enim ipsum aliqua in reprehenderit dolore nostrud culpa. Excepteur nulla tempor velit commodo incididunt consectetur consequat esse veniam laborum aliquip. Veniam non veniam excepteur occaecat voluptate nostrud mollit consequat mollit. Mollit consectetur Lorem exercitation nisi enim pariatur voluptate enim occaecat elit tempor excepteur esse irure.\r\n",
        "registered": "2020-01-14T12:29:33 -07:00",
        "latitude": -27.588234,
        "longitude": -133.481719,
        "tags": [
          "sint",
          "qui",
          "cupidatat",
          "anim",
          "eu",
          "ad",
          "laboris"
        ],
        "friends": [
          {
            "id": 0,
            "name": "Sharp Shepard"
          },
          {
            "id": 1,
            "name": "Merritt Mejia"
          },
          {
            "id": 2,
            "name": "Tanner Duke"
          }
        ],
        "greeting": "Hello, James Macdonald! You have 7 unread messages.",
        "favoriteFruit": "strawberry"
      },

