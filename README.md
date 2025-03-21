License Plate:
- uses Key `x-api-key` with Value `my_secure_api_key` on Postman.

User Signup:
- To sign up:
  - Sent a PUT request to `http://localhost:3000/user/signup`
    with a JSON body of:
      `{
  "firstName": "Martha",
  "lastName": "Stewart",
  "email": "martha.stewart@example.com",
  "password": "ilovegardening123"
}`

- Change the `EMAIL_USER` in .env to your email to send the activation link
- To resend activation token, send `GET` request to `http://localhost:3000/user/sendActivationToken/martha.stewart@example.com`
