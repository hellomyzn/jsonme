# JsonMe

JsonMe is a service that allows you to publish your profile information as an API.  
After registering an account, you can add details like your favorite music, movies, and hobbies.  
A unique endpoint will be generated for you, and you can easily retrieve your profile information in JSON format via `curl` or any HTTP request.

This project is inspired by the idea of [JSON Resume](https://jsonresume.org/).

## Features

- Freely register and update your profile information
- Auto-generated API endpoint for each user
- Retrieve information in simple JSON format
- Public access without authentication (optional)

## Example Usage

```bash
curl https://jsonme.app/users/your-username
```

Example response:

```json
{
  "name": "Eishi Miyazono",
  "nationality": "Japan",
  "favorite_music": "Lofi HipHop",
  "favorite_movie": "Interstellar"
}
```
