# Northcoders News API

1. .env - Create two .env files (.env.test and .env.development). In each one, insert "PGDATABASE=" followed by the relevant database name (found in setup.qsql).

FOR FURTHER DETAIL ON ENDPOINTS SEE ENDPOINTS.JSON

2. GET /api endpoint - shows the endpoints, each with a short description.

3. GET /api/topics endpoint - returns an array of topics

4. GET /api/articles/:article_id - returns an article object with the specified id

5. GET /api/articles - returns an array of all articles

6. GET /api/articles/:article_id/comments - returns comments for given article

7. POST /api/articles/:article_id/comments - posts a new comment

8. PATCH /api/articles/:article_id - updates the number of votes for an article

9. DELETE /api/comments/:comment_id - deletes a comment with specified id (if comment exists)

10. GET /api/users - returns an array of users

This portfolio project was created as part of a Digital Skills Bootcamp in Software Engineering provided by [Northcoders](https://northcoders.com/)
