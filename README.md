# Fresh Tomatoes

## CRUD table

| URL                  | HTTP Verb    | Action   | What it does             | Status   |
| -------------------- | ------------ | -------- | ------------------------ | -------- |
| /reviews or /        | GET          | index    | See all reviews          | done     |
| /reviews/new         | GET          | new      | See new review form      | done     |
| /reviews             | POST         | create   | Create a new review      | done     |
| /reviews/:id         | GET          | show     | Show a single review     | done     |
| /reviews/:id/edit    | GET          | edit     | See the edit review form | done     |
| /reviews/:id         | PUT or PATCH | update   | Edit a single review     | done     |
| /reviews/:id         | DELETE       | destroy  | Delete a single review   | done     |
| COMMENTS             | COMMENTS     | COMMENTS | COMMENTS                 | COMMENTS |
| /review/comments     | POST         | create   | Create a single comment  | done     |
| /review/comments/:id | DELETE       | destroy  | Delete a single comment  | hw       |

...

### Day 1

- CRUD
- MONGODB (document)
- Mongoose ODM (schema, model)
- environment variables in Node apps

### Day 2

- CRUD

### Day 3

- Cleanup
- Bootstrap styling
- Add test (finish testing by yourself)

### Day 4

- Depolyment

### Day 5

- Comments
- Created a comment form (title, content)
- Show comment form inside review page
- Create a comment post api
- Associate Comment with Review
- Save comment to database and then redirect to same review page
- Show comments
- Delete comment => /review/
