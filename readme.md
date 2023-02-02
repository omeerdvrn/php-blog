
# PHP Blog CRUD API
Simple API for blog posts.


## Technologies


**PHP** 

  
## API Usage

#### Create a post

```http
  POST /api/post/create.php
```

| Parameter | Type     | Description                |
| :-------- | :------- | :-------------------------------- |
| `title`      | `string` | Title of the post you are creating. |
| `body`      | `string` | Body of the post you are creating. |
| `author`      | `string` | Author of the post. |
| `category_id`      | `number` | The category id of the post you are creating. |
| `category_name`      | `string` | The category name of the post you are creating. |

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
| `id`      | `number` | Id of the post that you are updating. |
| `title`      | `string` | Title of the post you are updating. |
| `body`      | `string` | Body of the post you are updating. |
| `author`      | `string` | Author of the post. |
| `category_id`      | `number` | The category id of the post you are updating. |
| `category_name`      | `string` | The category name of the post you are updating. |




#### Delete a post

```http
  DELETE /api/post/delete.php?id={id}
```

| Parameter | Type     | Description                |
| :-------- | :------- | :-------------------------------- |
| `id`      | `number` | Id of the post that you delete. |
  
