# BookMovieClub (personal project)
Create a big book/movie club open source project do have book/movie recommendation and book/movie club functionalities (maybe also other form of entertainment such as videogames, board games or rpg such as D&D, tv series, etc)

# Features (to implement in future)
- Create a recommendation system: where based on user data (preferences and/or read/rated books/movies) will score (numerical or other format) books so as to find the highest scored to be recommended (CORE)
  - Insert, update and remove user preferences and read/rated books/movies data
  - Generate a general review rating data for books based on information obtained from APIs (IMDB, rotten tomatoes, etc) (only use this a very general 'confidence' rating using different metrics such as rating, number of reviews, number of comments, rating based only on comments?, etc )
  - Use user data and general review rating data to rate recommendation scores on the available books/movies (only need to store the highest x rated ones for the user?)
- Book/Movie club automatic session creation: (CORE)
  - Creates a book/movie club with a group of users with matching recommended books/movies (users that have agreed/signed up for a book/movie club session)
  - Add functionality for catered selection of groups to interest such as:
    - age range preference
    - user gender preference
    - book/movie genre preference
    - (international) time zone / location preference
    - time block limitation / preference (could be for time of meeting or regularity of meeting such as once a week, once a month, etc)
    - etc
  - Insert, update and remove of book/movie club session data
  - Access user book/movie recommendation data
- Interface with book/movie club meeting facilitators (NON CORE)
  - Interface with a physical location or digital meeting service (or make one) to organize the meeting location and actual meeting
  - Interface with purchase/rent services to give easy options for users to obtain the book/movie for the current session
  - ADs/paid promotion of books/movies? (could be on the book/movie club service or could be with sponsored book/movie club sessions for recently released books/movies) ( could be free/reduced price if its a paid service or if everything is free then it could be special limited edition ones with certain perks or something different to regular ones such as more people per session or specifically tailored ones for the promoted/sponsored content such as the lesson plan or even guest speakers?)
- Manage Employees? (NON CORE)
  - There are employees to provide human interaction services such as:
    - customer support such as manual interaction with the club sessions (manual add, remove, update)
    - developers to maintain, fix, add features
    - Club Session Masters which could be in charge of running some or all book club session in which they facilitate, plan and/or do activites for the different club sessions
