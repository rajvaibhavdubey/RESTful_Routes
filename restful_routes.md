| **URL** | **HTTP Verb** |  **Name**|    **Purpose**|
|------------|-------------|-------------|-----------|
| /posts/         | GET       | index    |Lists all Posts
| /posts/new      | GET       | new      |Shows A new post form
| /posts          | POST      | create   |Creates a new post then redirects somewhere
| /posts/:id      | GET       | show     |Shows info about one specific post
| /posts/:id/edit | GET       | edit     |Shows edit form for one specific post
| /posts/:id      | PUT       | update   |Updates a specific post then redirects somewhere
| /posts/:id      | DELETE    | destroy  |Deletes a specific post , then redirects somewhere
