## Hoseki iOS Coding Challenge

For applicants applying for iOS engineer position

#### Summary

Write a scrolling movie list app using TheMovieDB API. Movies can be tapped to view on a details screen. 

#### Requirements

1. Create a scrolling list to show trending movies from the last week using the following endpoint from TheMovieDB:
https://developers.themoviedb.org/3/trending/get-trending
1. Make a movie detail screen so the user can further drill down into the result
1. Both the detail and the list screens should show the movie poster 
1. Include instructions for building the application and any relevant documentation in a README.md file
1. Please post your submission on Github, Bitbucket or Gitlab

The following is a rough idea of what the screens should look like:
<p align="center">
  <img src="https://github.com/shmanny/iOS-Coding-Challenge/blob/main/demo.gif" alt="Hoseki iOS Challenge"/>
</p>

#### Optional
1. The movie detail screen should allow users to like/unlike the movie
1. Liked movies should be saved between launches of the app

#### Guidelines

The challenge will be judged on

1. Architectural choices 
2. Code organization and testability
3. Understanding of iOS libraries and SDKs

The challenge will NOT be judged on

1. Aesthetics and design

Please write your code in Swift. Feel free to use any third party, open source libraries and design the UI however you like. 

#### API Information

The endpoint on TheMovieDB is free and publicly accessible, but you will need to register for an account at their website: https://www.themoviedb.org. Once you've registered, click your profile icon in the top right > Settings > API and you should be able to request an API key after filling out the form (you can fill it out with dummy data).

Once you've received your key, you will pass it in the query string of `api_key` with the trending movies query. 
The below query will give the trending movies list:
```
https://api.themoviedb.org/3/trending/movies/week?api_key={your_api_key}
```

Full API documentation is available at https://developers.themoviedb.org/3/getting-started/introduction
