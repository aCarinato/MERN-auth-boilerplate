Boilerplate containing authentication functionalities with MERN stack. These include:

- navigation links (with current page active link)
- register
- login
- reset password
- dashboard page for authenticated user (with nav link displaying the username)

## Environment variables

### Client

In the client folder this file has to be added:

- .env.local

which should contain the following environment variables:

```
- NEXT_PUBLIC_API=http://localhost:8000/api
```

### Server

In the server folder this file has to be added:

- .env

which should contain the following environment variables:

```
- DATABASE=mongodb+srv://<MongoDBUserName>:<MongoDBPassword>@<MongoDBClusterName>.mongodb.net/<DatabaseName>?retryWrites=true&w=majority
- PORT=8000
- JWT_SECRET=<YOURJWTSECRET>
```

In the DATABASE variable replace fields within '< >' with MongoDB credentials and remove '< >'
