you can run this file using  <mark> nodemon index.js</mark>

### Authentication Endpoints

| Method | Route        | Description                  |
|--------|--------------|------------------------------|
| POST   | /register     | Register a new user          |
| POST   | /login        | Log in as an existing user   |
| GET    | /logout       | Log out the current user     |

##
### Book Endpoints

| Method | Route            | Description                    |
|--------|------------------|--------------------------------|
| GET    | /book            | Fetch all book                 |
| POST   | /book            | Create a new book              |
| PATCH  | /book/:id        | Update an existing book        |
| DELETE | /book/:id        | Delete a book                  |
| DELETE | /book/borrow/:id | borrow the book                |
| DELETE | /book/return/:id | return the book                |
