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

- Routes: controller funcs

                   GetBooks<--/book/<--GET
                   CreateBook<--/book/<--POST
                   GetBookByID<--/book/{bookId}<--GET
                   UpdateBook<--/book/{bookId}<--PUT
                   DeleteBook<--/book/{bookId}<--DELETE 
