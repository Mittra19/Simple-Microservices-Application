Our Post service needs to perform two tasks.

1. Create a post
2. Retrieve all the posts

For that we need one route called `/posts`.

### Post Service

|  Path  | Mathod |      Body      |        Goal        |
| :----: | :----: | :------------: | :----------------: |
| /posts |  POST  | {title:string} |  Create new post   |
| /posts |  GET   |       -        | Retrieve all posts |

# Steps to implement:

- `npm init -y` - To initialize the package.json file
- `npm install express cors axios nodemon` - To install the packages express, cors, axios, and nodemon
- Write the required code in index.js
- Remove the `"test": "echo \"Error: no test specified\"` && exit 1" from package.json file and add `"start: : "nodemon index.js"` in the scripts object.
- Open Postman and send a post request to localhost:PORT/posts.
- `npm install cors` - To stop cors error
