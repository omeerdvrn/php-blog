
# PHP Blog CRUD API
Simple API for blog posts.


## Technologies


**PHP** 

  
## Post Structure

```json
{
    "id": 101,
    "title": "TITLE",
    "body": "Lorem ipsum dolor sit amet, consectetur adipiscing elit.",
    "author": "God",
    "category_id": 1,
    "category_name": "Technology"
}
```

  
## API Usage

#### Create a post

```http
  POST /api/post/create.php
```

| Parameter | Type     | Description                |
| :-------- | :------- | :-------------------------------- |
| `title`      | `string` | Title of the post you create. |
| `body`      | `string` | Body of the post you create. |
| `author`      | `string` | Author of the post. |
| `category_id`      | `number` | The category id of the post you create. |
| `category_name`      | `string` | The category name of the post you create. |

#### Read all posts

```http
  GET /api/post/read.php
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `-` | `-` | - |

#### Read single post

```http
  GET /api/post/read_single.php?id={id}
```

| Parameter | Type     | Description                |
| :-------- | :------- | :-------------------------------- |
| `id`      | `number` | Id of the post that you read. |


#### Update a post

```http
  PUT /api/post/update.php
```

| Parameter | Type     | Description                |
| :-------- | :------- | :-------------------------------- |
| `id`      | `number` | Id of the post that you update. |
| `title`      | `string` | Title of the post you update. |
| `body`      | `string` | Body of the post you update. |
| `author`      | `string` | Author of the post. |
| `category_id`      | `number` | The category id of the post you update. |
| `category_name`      | `string` | The category name of the post you update. |




#### Delete a post

```http
  DELETE /api/post/delete.php?id={id}
```

| Parameter | Type     | Description                |
| :-------- | :------- | :-------------------------------- |
| `id`      | `number` | Id of the post that you delete. |
  
  
