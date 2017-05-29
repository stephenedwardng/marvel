# SQL Homework

The Glasgow Film Theatre are having a Marvel Movie Marathon! They have asked you to help maintain their database of movies with times and attendees.

## To access the database:

First, create a database called 'marvel'
```
# terminal
createdb marvel
```

Next, run the provided SQL script to populate your database:
```
# terminal
psql -d marvel -f marvel.sql
```

Use the supplied data as the source of data to answer the questions.  Copy the SQL command you have used to get the answer, and paste it below the question, along with the result they gave.

## Questions

1. Return ALL the data in the 'movies' table.
2. Return ONLY the name column from the 'people' table
3. Oops! Someone at CodeClan spelled Graham's name wrong! Change it to reflect the proper spelling ('Graeme Broose' should be 'Graham Bruce').
4. Return ONLY your name from the 'people' table.
5. The cinema is showing 'Batman Begins', but Batman is DC, not Marvel! Delete the entry from the 'movies' table.
6. Create a new entry in the 'people' table with the name of one of the instructors.
7. Harvey Wheaton has decided to hijack our movie evening, Remove him from the table of people.
8. The cinema has just heard that they will be holding an exclusive midnight showing of 'Spider-man: Homecoming'!! Create a new entry in the 'movies' table to reflect this.
9. The cinema would also like to make the Guardian movies a back to back feature. Update the 'Guardians of the Galaxy' show time from 15:30 to 20:00

## Extension

1. Research how to delete multiple entries from your table in a single command.
