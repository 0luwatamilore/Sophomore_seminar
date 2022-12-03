# Sophomore_seminar
Book Search Demo
Android app that leverages the OpenLibrary API to search books and display cover images. It also allows you to recommend books to friends. See the Book Search Tutorial on our cliffnotes for a step-by-step tutorial.

The app is composed of two screens. The first screen displays a list of books, in which, each book is described by its title, author and cover photo. After a user selects a book from the list, a second screen appears displaying additional details about the book, including the publisher and no. of pages.

Book List

Imgur

Book Details

Imgur

Overview
The app does the following:

Search a list of books using the OpenLibrary Search API
Display the list of books with their cover images and details
Replace ActionBar with Toolbar
Use SearchView to search for books with a title
Show ProgressBar before each network request
Add a detail view to display more information about the selected book from the list
Use a share intent to recommend a book to friends
To achieve this, there are five different components in this app:

BookClient - Responsible for executing the API requests and retrieving the JSON
Book - Model object responsible for encapsulating the attributes for each individual book
BookAdapter - Responsible for mapping each Book to a particular view layout
BookListActivity - Responsible for fetching and deserializing the data, configuring the adapter and providing a search interface
BookDetailActivity - Responsible for providing book detail view and share intent.
See the Book Search Tutorial on our cliffnotes for a step-by-step tutorial.

Libraries
This app leverages two third-party libraries:

Android AsyncHTTPClient - For asynchronous network requests
Picasso - For remote image loading
