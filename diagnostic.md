# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.

What is the purpose of a backend?

```bash
The back end, or server side, is code that remains on the server.
```

Which layer in the MVC pattern is used by the controller to fetch data?

```bash
Server
```

Which layer in the MVC pattern communicates with the model?

```bash
Controller
```

Why don't we use views in our interpretation of the MVC pattern?

```bash
Controller handles events from the view.
```

What does C.R.U.D stand for?

```bash
Create, Read, Update, Destroy
```

In which part of the MVC pattern can we find C.R.U.D actions?

```bash
Client
```

List at least 5 standard rails actions that C.R.U.D requests correspond to?

```bash
index, create, show, update, destroy
```

A user action fires a `GET` request for `/people/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list)

```bash
Client goes to the server which then sends data to the proper controller after that the controller sends data over to the model which then comes back to the server and then the client.
```

What is the command to generate a new rails-api app?

```bash
rails new app_name
```

What is the command to start an instance of a rails server?

```bash
bundle exec rails server
```

What are the commands to drop, create and migrate a database from the command
line? (3 bullet points)

```bash
db:drop
db:create
db:migrate

```

What is the command to scaffold a pet with a name and age attributes (hint:
Also think of the data types for each attribute)?

```bash
bin/rails generate scaffold Pet name:string age:integer
```
