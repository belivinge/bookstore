# Bookstore Management APIS

Beginner Friendly

1. Database - MySQL
2. GORM
3. Json marshall, unmarshall
4. Project structure
5. Gorilla mux

- Project structure:

                   PKG->config->app.go
                      ->controllers->book-controller
                      ->models->book-go
                      ->routes->bookstore-routes
                      ->utils->utils.go

                   CMD->main.go

we can use " mkdir -p pkg/config pkg/controllers pkg/models pkg/routes pkg/utils " to create the folder structure quickly

- Routes: controller funcs

                   GetBooks<--/book/<--GET
                   CreateBook<--/book/<--POST
                   GetBookByID<--/book/{bookId}<--GET
                   UpdateBook<--/book/{bookId}<--PUT
                   DeleteBook<--/book/{bookId}<--DELETE 
