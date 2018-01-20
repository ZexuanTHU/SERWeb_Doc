# add_teammate()
## Declaration
`add_teammate(request, user_id, project_id)`

## API url
**POST** http:\\localhost:8000\api\add_teammate\\`user_id`\\`project_id`

`user_id`, `project_id` *are their pk values in the database*

POST body 需要传一个name参数(已经注册用户的真实姓名，与user_info中的name对应）