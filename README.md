
## PC Performance Tracker

http://a3-andrewrm98.glitch.me

- The goal of this application is to provide an easy way to track your PC's performance over time and give feedback on how it compares to other PCs
- The biggest challenge was getting express and cookies to work
- I also struggled getting the tables to allow for modification and deletion. They do in fact allow this (just click on a cell to edit it, and the rightmost column with the x in it for deleting the row), but unfortunately I ran out of time and was not able to get this to persist to the database. I am not sure if that is necessarily required, but is definitely something I want to add in the future
- I used lowdb since it was simple and lightweight
- I used an authentication based off of my own user database because it made sense to me
- I used Bulma and Tabulator for CSS. Bulma provides a lot of CSS classes for you and made styling very quick and simple. Tabulator takes care of my tables and makes them clean and even provides styling for them as well.
- I also authored a lot of my own CSS for many miscellaneous things such as the size of things, font color, rounding the edges of my divs, giving things borders, and positioning them on the screen
- The five packages were: passport (for user authentication), express-session (for user cookies), body-parser (for parsing JSON objects), passport-local (for passport strategies), express (for server side route handling)

## Technical Achievements
- **Tech Achievement 1**: I used passport to verify usernames and passwords contained in a lowdb database
- **Tech Achievement 2**: I used 5 Express middleware packages allowing me create a more readable server with authentication and cookies
- **Tech Achievement 3**: I allow a user to signin to see their own performances, as well as seeing everybody's performances when not logged in. I also implemented a signout button that will destroy the current session.
- **Tech Achievement 4**: I provide automatic redirects when logging in, and logging out (different redirects for failures and successes)
- **Tech Achievement 5**: I used a simple algorithm to rate your PC's health, as well as provide some simple statistics based off of all of your performance entries

### Design/Evaluation Achievements
- **Design Achievement 1**: I used Bulma for CSS classes that allowed me to style quickly, as well as provide scaling for different resolutions
- **Design Achievement 2**: I used Tabulator to create stylish tables that allow for editing and deletion
