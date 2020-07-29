# omdb_dart

Dart client for the www.omdbapi.com API . it will return movie detials like year,IMDB Rating, actors,directors,poster and much more  

# Getting Started
To run or use this package you'll need to first get an API key from [http://omdbapi.com](http://www.omdbapi.com/apikey.aspx).

# Now import it 

```dart
    import 'package:omdb_dart/omdb_dart.dart';
```

# How to Use

Create a object of Omdb class and pass API KEY and movie name.

```dart
    Omdb client = new Omdb("KEY", "MOVIE");
```

Get details
```dart
    print("Title : ${client.movie.title}"); // print Title of the movie
    print("Released : ${client.movie.released}"); //print Released Date
    print("Runtime : ${client.movie.runtime}"); //runtime
    print("Poster URL : ${client.movie.poster}"); //URL of poster
    print("Director :${client.movie.director} "); //Director
    print("Writer :${client.movie.writer} ");
    print("Actors :${client.movie.actors} ");
    print("Plot :${client.movie.plot} ");
    print("Language :${client.movie.language} ");
    print("Country :${client.movie.country} ");
    print("Awards :${client.movie.awards} ");
    print("Meta Score :${client.movie.metascore} ");
    print("IMDB Rating :${client.movie.imdbRating} ");
    print("IMDB Votes :${client.movie.imdbVotes} ");
    print("IMDB ID :${client.movie.imdbID} ");
    print("Website :${client.movie.website} ");
    print("Production :${client.movie.production} ");
    print("Box Office :${client.movie.boxOffice} ");
```
Created By [Viral Vaghela](https://github.com/viralvaghela)
