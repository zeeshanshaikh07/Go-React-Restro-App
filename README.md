
# Go-React Restro App

This the the repo for my fullstack restaurant app in which the server is Golang, the database is MongoDB, and the frontend is in React.


## Tech Stack
**Server:** Go

**Client:** React, Bootstrap

**Database:** MongoDB
## Run Locally

Clone the project

```bash
  git clone https://github.com/zeeshanshaikh07/Go-React Restro App.git
```

Go to the project directory

```bash
  cd Go-React Restro App
```
### MongoDB

We are going to use the official MongoDB Go Driver from MongoDB.
To install it run the below command in the terminal or command window.

```bash
  go get go.mongodb.org/mongo-driver
```

### Backend API

Second, install the gorilla/mux package for the router. mux is one of the most popular packages for the router in the Golang.
To install it run the below command in the terminal or command window.

```bash
  go get -u github.com/gorilla/mux
```
we can now build and run our server, First navigate to the server directory and enter the following commands:

```bash
  go mod tidy
  go build main.go
  go run main.go
```
### Front End
Once the app is created, navigate to the frontend directory and enter the following commands to install dependencies

```bash
  npm install
  npm install axios
  npm install react-bootstrap@next bootstrap@5.1.0
```

Start the server

```bash
  npm start
```
Go to http://localhost:5000
