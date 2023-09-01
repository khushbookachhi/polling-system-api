# polling-system-api
This is a backend api for creating questions and adding options to a specific question.Options can be voted. Questions, options can be deleted and questions can be viewed with all of their options.

# Features
1. Create questions
2. Add options to question
3. Delete a question
4. Delete an option
5. Add vote to an option
6. View a question with all of its options

# Usage
1. Run npm start to start the application.
2. Connect to the API using Postman on port 8000.


# API Endpoints
| HTTP request| Endpoints                    | Action  |
| ------------|:----------------------------:| -----:|
| POST        | /questions/create            | To create a question                  |
| POST        | /questions/:id/options/create| To add options to a specific question |
| DELETE      | /questions/:id/delete        |   To delete a question                |
| DELETE      | /options/:id/delete          | To delete an option  |
| PUT         | /options/:id/add_vote        | To increase the count of votes                     |
| GET         | /questions/:id               |To view a question and its options              |
