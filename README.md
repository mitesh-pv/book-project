# Summary

Book tracker web app made using Spring Boot and Vaadin 14 (only the free components will be used).

*Coming soon:*
- Add books that you have read to a 'read' shelf
- Add books that you are currently reading to a 'currently reading' shelf
- Add books that you would like to read to a 'want to read' shelf
- Add your own shelves
- View books in your different shelves and make changes
- And more!

<p align="center">
    <img src="/media/book-form.png" alt="New book form"/>
</p>

![Books in shelf](/media/books_in_shelf.png)

*The images above may look slightly different to the app. If major changes are made, new images will be uploaded to 
reflect this.*

# Setup

Prerequisites: JDK 11 (or higher), Node.js and npm

1. Clone the repository
2. Import the project as a maven project into your favourite IDE (or run maven on the terminal)
3. Run `BookProjectApplication.java`
4. Go to `localhost:8080`

To access the h2 database:

![H2](/media/h2.png)

1. Go to `http://localhost:8080/h2-console`
2. Ensure you have the settings as shown in the screenshot above
3. Click on connect

# Contributing

If you wish to contribute (thanks!), please first see the [contributing document](https://github.com/knjk04/book-project/blob/master/CONTRIBUTING.md).

# Further information

For more information, such as a roadmap and the underlying principles of the project, see the [Book Project wiki](https://github.com/knjk04/book-project/wiki).
