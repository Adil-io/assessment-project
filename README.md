# &Chill WebSite
###### Nowadays, multimedia entertainment has become a big industry and is growing everyday. There are various sources of entertainment like movies, television, books, music, etc. The users that want to access these different forms of data have to create id’s on various different sites. To make it easier for a person to access this data we have created a website that provides all the data of different fields in the same place, ‘&Chill’ provides users data related to their favourite movies, tv-shows, books, music. 

## Technologies
* HTML
* CSS
* JAVASCRIPT
* AJAX
* BOOTSTRAP
* jQuery

## ENDPOINTS
* TV 
     * QuerySearch https://api.themoviedb.org/3/search/tv?api_key=${api_key}&query=${query.value}
     * QueryDetails https://api.themoviedb.org/3/tv/${tv_id}?api_key=${api_key}&language=en-US
     * QuerySeasonDetails https://api.themoviedb.org/3/tv/${tv_id}/season/${seasonNo}?api_key=${api_key}&language=en-US
     * QueryVideos https://api.themoviedb.org/3/tv/${tv_id}/videos?api_key=${api_key}&language=en-US
     * TV OnAir https://api.themoviedb.org/3/tv/on_the_air?api_key=abdca3eea1b7fb0c1f10423e2fc33135
     * TV TopRated https://api.themoviedb.org/3/tv/top_rated?api_key=abdca3eea1b7fb0c1f10423e2fc33135

* Movies 
         * QuerySearch https://api.themoviedb.org/3/search/movie?api_key=abdca3eea1b7fb0c1f10423e2fc33135&query=${query.value}
         * QueryDetails https://api.themoviedb.org/3/movie/${movie_id}?api_key=abdca3eea1b7fb0c1f10423e2fc33135
         * QueryVideos https://api.themoviedb.org/3/movie/${movie_id}/videos?api_key=abdca3eea1b7fb0c1f10423e2fc33135
         * Movies NowPlaying https://api.themoviedb.org/3/movie/now_playing?api_key=abdca3eea1b7fb0c1f10423e2fc33135
         * Movies Upcoming https://api.themoviedb.org/3/movie/upcoming?api_key=abdca3eea1b7fb0c1f10423e2fc33135
         * Movies TopRated https://api.themoviedb.org/3/movie/top_rated?api_key=abdca3eea1b7fb0c1f10423e2fc33135
         
* Books 
         * QueryDetails https://itunes.apple.com/search?country=us&term=${query.value}&media=ebook&entity=ebook         

##Live Links
Resume https://adil-io.github.io
assessment-project https://adil-io.github.io/assessment-project/books.html


 
 
