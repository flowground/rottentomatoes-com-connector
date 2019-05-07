# ![LOGO](logo.png) Rotten Tomatoes **flow**ground Connector

## Description

A generated **flow**ground connector for the Rotten Tomatoes API (version 1.0).

Generated from: https://api.apis.guru/v2/specs/rottentomatoes.com/1.0/swagger.json<br/>
Generated at: 2019-05-07T17:43:55+03:00

## API Description

Test our API services using I/O Docs.

## Authorization

Supported authorization schemes:
- API Key
## Actions

### ListsDirectoryTopLevelLists

*Tags:* `Top Level Lists`

### DVDListsDirectoryTopLevelLists

*Tags:* `Top Level Lists`

### CurrentReleaseDVDsDVDLists

*Tags:* `DVD Lists`

#### Input Parameters
* `page_limit` - _optional_ - The amount of new release dvds to show per page
* `page` - _optional_ - The selected page of current DVD releases
* `country` - _optional_ - Provides localized data for the selected country (ISO 3166-1 alpha-2) if available. Otherwise, returns US data.

### NewReleaseDVDsDVDLists

*Tags:* `DVD Lists`

#### Input Parameters
* `page_limit` - _optional_ - The amount of new release dvds to show per page
* `page` - _optional_ - The selected page of new release DVDs
* `country` - _optional_ - Provides localized data for the selected country (ISO 3166-1 alpha-2) if available. Otherwise, returns US data.

### TopRentalsDVDLists

*Tags:* `DVD Lists`

#### Input Parameters
* `limit` - _optional_ - Limits the number of top rentals returned
* `country` - _optional_ - Provides localized data for the selected country (ISO 3166-1 alpha-2) if available. Otherwise, returns US data.

### UpcomingDVDsDVDLists

*Tags:* `DVD Lists`

#### Input Parameters
* `page_limit` - _optional_ - The amount of upcoming dvds to show per page
* `page` - _optional_ - The selected page of upcoming DVDs
* `country` - _optional_ - Provides localized data for the selected country (ISO 3166-1 alpha-2) if available. Otherwise, returns US data.

### MovieListsDirectoryTopLevelLists

*Tags:* `Top Level Lists`

### BoxOfficeMovieLists

*Tags:* `Movie Lists`

#### Input Parameters
* `limit` - _optional_ - Limits the number of movies returned
* `country` - _optional_ - Provides localized data for the selected country (ISO 3166-1 alpha-2) if available. Otherwise, returns US data.

### InTheatersMovieLists

*Tags:* `Movie Lists`

#### Input Parameters
* `page_limit` - _optional_ - The amount of movies in theaters to show per page
* `page` - _optional_ - The selected page of in theaters movies
* `country` - _optional_ - Provides localized data for the selected country (ISO 3166-1 alpha-2) if available. Otherwise, returns US data.

### OpeningMoviesMovieLists

*Tags:* `Movie Lists`

#### Input Parameters
* `limit` - _optional_ - Limits the number of opening movies returned
* `country` - _optional_ - Provides localized data for the selected country (ISO 3166-1 alpha-2) if available. Otherwise, returns US data.

### UpcomingMoviesMovieLists

*Tags:* `Movie Lists`

#### Input Parameters
* `page_limit` - _optional_ - The amount of upcoming movies to show per page
* `page` - _optional_ - The selected page of upcoming movies
* `country` - _optional_ - Provides localized data for the selected country (ISO 3166-1 alpha-2) if available. Otherwise, returns US data.

### MoviesAliasDetailedInfo

*Tags:* `Detailed Info`

#### Input Parameters
* `id` - _optional_ - Movie ID. You can use the movies search endpoint or peruse the lists of movies/dvds to get the Movie ID
* `type` - _optional_ - Only supports imdb lookup at this time

### MoviesSearchSearch

*Tags:* `Search`

#### Input Parameters
* `q` - _optional_ - The plain text search query to search for a movie. Remember to URI encode this!
* `page_limit` - _optional_ - The amount of movie search results to show per page
* `page` - _optional_ - The selected page of movie search results

### MoviesInfoDetailedInfo

*Tags:* `Detailed Info`

#### Input Parameters
* `id` - _required_ - Movie ID. You can use the movies search endpoint or peruse the lists of movies/dvds to get the Movie ID

### CastInfoDetailedInfo

*Tags:* `Detailed Info`

#### Input Parameters
* `id` - _required_ - Movie ID. You can use the movies search endpoint or peruse the lists of movies/dvds to get the Movie ID

### MovieClipsDetailedInfo

*Tags:* `Detailed Info`

#### Input Parameters
* `id` - _required_ - Movie ID. You can use the movies search endpoint or peruse the lists of movies/dvds to get the Movie ID

### MoviesReviewsDetailedInfo

*Tags:* `Detailed Info`

#### Input Parameters
* `id` - _required_ - Movie ID. You can use the movies search endpoint or peruse the lists of movies/dvds to get the Movie ID
* `review_type` - _optional_ - 3 different review types are possible: 'all', 'top_critic' and 'dvd'. 'top_critic' shows all the Rotten Tomatoes designated top critics. 'dvd' pulls the reviews given on the DVD of the movie. 'all' as the name implies retrieves all reviews.
* `page_limit` - _optional_ - The number of reviews to show per page
* `page` - _optional_ - The selected page of reviews
* `country` - _optional_ - Provides localized data for the selected country (ISO 3166-1 alpha-2) if available. Otherwise, returns US data.

### MoviesSimilarDetailedInfo

*Tags:* `Detailed Info`

#### Input Parameters
* `id` - _required_ - Movie ID. You can use the movies search endpoint or peruse the lists of movies/dvds to get the Movie ID
* `limit` - _optional_ - Limit the number of similar movies to show

## License

**flow**ground :- Telekom iPaaS / rottentomatoes-com-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
