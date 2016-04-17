Group project. Takes commandline input and uses Twitter API to spit out tweets. Saves to MySQL database.

My part of the project is the interaction with the MySQL database. Since Javascript is asynchronous, saving tweets before the database connection closes out was incredibly roundabout and unnecessarily complicated. I ended up using the async model and writing very long code.

Link to project: https://github.com/Oh-Petya/CSC314TwitterProject
