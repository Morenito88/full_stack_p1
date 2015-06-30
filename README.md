Movie Trailer Website  Version 1.1  06/30/2015

What is it?
-----------

The Movie Trailer Website is a library where you 
can add and see the latest movie trailers and information about it.

How to use
------------

If you want to add/edit the movies just do the following steps:

1 - Go to "center.py" file

2 - Create a new Movie instance with this format:

    movieX = movie.Movie(MOVIE_NAME,
                           MOVIE_DESCRIPTION,
                           MOVIE_RELEASE_DATE,
                           MOVIE_RATING,
                           MOVIE_POSTER_IMAGE,
                           MOVIE_GOTO_SLIDER,
                           MOVIE_SLIDER_IMAGE,
                           MOVIE_TRAILER_URL)
                         
3 - Add "movieX" to "movies" list. Ex:
    
    movies = [jurassic_world, avengers, san_andreas, entourage, mad_max, guardians, tomorrowland, movieX]
    
How to run
------------

You can run the application in any Python IDE or directly from 
terminal using the command:

    python center.py
    
It will generate an .html file with all the movies content and 
automaticaly open it on web browser.

Licensing
---------

Please see the file LICENSE.

Contacts
--------

o If you want to be informed about new code releases, bug fixes,
security fixes, general news and information about the Movie Trailer
Website project just keep tracking this repository.

o If you want freely available support for running this application 
or any kind of help just mail <hugophp@sapo.pt>
