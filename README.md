## An API server for my Todo Application
This is a simple, single file .Net REST API to serve as a backend
for another one of my projects, a Windows native client application
written in Delphi (Object Pascal).
You can find it [here](https://github.com/Sockney89/TodoApp).


While I specifically built this little API for the Delphi client
application, you can still clone it and have a play with it.

- make sure you have .Net 9.0 or newer installed
- clone repo
- from project root run `dotnet run` . This will install necessary dependencies and run the server.
- navigate to `localhost:5249/swagger` for a Swagger API documentation.

> The API server uses SQLite to persist your Todos.

Have fun, and I always welcome feedback or comments if you have any!