# APITest
This is a standard RestAPI implementation with go and gin framework

install go, mysql
make sure you vendor all the libraries with 
```bash
go mod vendor
```
Create the database and build the config in Database.go. Add host, username, password to connect to database

start the server using
```bash
go run main.go
```

You can test the following apis with CURL or postman

- GET user-api/user → Retrieves all the user data
- POST user-api/user → Add new user data
- GET user-api/user/{id} → Retrieve the single user data
- PUT user-api/user/{id} → Update the user data
- DELETE user-api/user → Delete the user data
