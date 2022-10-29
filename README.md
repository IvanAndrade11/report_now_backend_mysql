## Url BD
https://www.freemysqlhosting.net/account/

## Server
https://dashboard.heroku.com/apps/report-now

## User Mailer Provider
* report.now.mailer@gmail.com


## API Reference

### Endpoint
* https://report-now.herokuapp.com

#### List all users

```http
  [GET] /api/users
```

#### Get user

```http
  [GET] /api/users/${id}
```

| Parameter | Type     | Description                       | Required           |
| :-------- | :------- | :-------------------------------- | :----------------- |
| `id`      | `number` | Id of user to search              | :white_check_mark: |

#### Create user

```http
  [POST] /api/users/create
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `user`    | `string` | **Required**. User to identify in Report Now |
| `name`    | `string` | **Required**. Full name of user |
| `email`   | `string` | **Required**. Email to sing in |
| `phone`   | `string` | **Required**. Phone to send notifications and code otp |
| `password`| `string` | **Required**. Password with specific characters |

#### Update user

```http
  [PUT] /api/users/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `number` | **Required**. Id of user to identity |
| `user`    | `string` | **Required**. User to identify in Report Now |
| `name`    | `string` | **Required**. Full name of user |
| `email`   | `string` | **Required**. Email to sing in |
| `phone`   | `string` | **Required**. Phone to send notifications and code otp |
| `admin`   | `boolean`| Param to create user admin |


## Authors

- [@IvanAndrade11](https://github.com/IvanAndrade11)

