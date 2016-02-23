## IMDb Movies Data Explorer

This Shiny App is for searching through the Movies data set information from year 1893 to 2005.  
The total number of set records is 10691 and that of theme records is 104.
  
Movie information and user ratings from IMDB.com.

Description

The internet movie database, http://imdb.com/, is a website devoted to collecting movie data supplied by studios and fans. It claims to be the biggest movie database on the web and is run by amazon. More about information imdb.com can be found online, http://imdb.com/help/show_leaf?about, including information about the data collection process, http://imdb.com/help/show_leaf?infosource.

Usage

data(movies)
Format

A data frame with 28819 rows and 24 variables

Details

Movies were selected for inclusion if they had a known length and had been rated by at least one imdb user. The data set contains the following fields:

**title** - Title of the movie.

**year** - Year of release.

**budget** - Total budget (if known) in US dollars

**length** - Length in minutes.

**rating** - Average IMDB user rating.

**votes** - Number of IMDB users who rated this movie.

**r1-10** - Multiplying by ten gives percentile (to nearest 10%) of users who rated this movie a 1.

**mpaa** - MPAA rating.

**Action, Animation, Comedy, Drama, Documentary, Romance, Short** - Binary variables representing if movie was classified as belonging to that genre.

**References**  
http://had.co.nz/data/movies/
