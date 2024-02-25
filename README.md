# Comment Service API

Welcome to the Comment Service API repository! This API provides endpoints for managing comments on products.

### Get Comment by ID
- **Endpoint:** `GET /v1/comments/{id}`
- **Description:** Retrieve details of a specific comment by ID.

### Save Comment
- **Endpoint:** `POST /v1/comments`
- **Description:** Create a new comment.

### Update Comment
- **Endpoint:** `PUT /v1/comments/{id}`
- **Description:** Update an existing comment.
- **Request Body:** [UpdateCommentRequest](#updatecommentrequest)

### Delete Comment
- **Endpoint:** `DELETE /v1/comments/{id}`
- **Description:** Delete a comment.

### Get Comments for a Product
- **Endpoint:** `GET /v1/comments/products/{id}`
- **Description:** Retrieve a list of comments for a specific product.

