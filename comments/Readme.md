### Comments Service

|        Path        | Method |      Body?       |                          Goal                           |
| :----------------: | :----: | :--------------: | :-----------------------------------------------------: |
| posts/:id/comments |  POST  | {content:string} |    Create a comments associated with a given post id    |
| posts/:id/comments |  GET   |        -         | Retrieve all comments associated with the given post id |

# Steps to implement:

- `npm init -y` - To initialize the package.json file
- `npm install express cors axios nodemon` - To install the packages express, cors, axios, and nodemon
- Write required code in index.js
- `npm install cors` - To stop cors error
