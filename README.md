This my NSS (part 1) Capstone project. This is an app that's purpose is for "movie nerds" to keep track of what they have seen and organize most popular data in a fashion to use for discussion later. First type a movie in a search bar. That search bar will display a list of movies depending on your input (which will reference omdb api). Once selecting a suggested movie a form with pre-loaded movie data will display and the user will enter a review along with some other info. Then this review and info will be stored in a table that can be sorted based on most popular information. I am doing GET, DELETE, POST with JSON objects in order to make this app functional.

What has been done prior to this (This whole section is completed):

-Creat a search bar that will have search results in a "auto suggestion" dropdown
	-connect to OMDBapi for search results
-When selecting a specific title, have OMDBapi to return (in JSON) that movie's info (poster, title, year, runtime, etc). 
-Have movie info to show up with a review form
-Add hidden inputs so movie info (from OMDBapi) can be submitted with the user's review to movieDatabase (Dane's backlift
database)
-Have a textarea for user to type review
-Add a submit button that will subit the review
-Add a canel button that will close the form and take out the movie info from the OMDBapi
-add a table that the form data can append to
-Make the title have a Popover from TwitterBootStrap that the review can be seen in as well as additional movie info


5/18/13:

added show and hide for the form, added the ability to put quotes in a review, added movie year to the review title, added a cancel button on form"
[master ae3148a] added show and hide for the form, added the ability to put quotes in a review, added movie year to the review title, added a cancel button on form

Phase 2(completed) - End of proposed functionality:

-add a table sorter plugin to UrMovieReviews (completed)
-set popover to display from the bottom (completed)
-have UrMovieReviews display (title, Ur Grade, RT Score, Year Released, Date Watched, Rating) - (completed)
-have popover display (review, runtime, release date, director, writer, actors, plot) - (completed)
-add a rating plugin and have it go to JSON object and display on table (completed)
-add a input for entering the data (maybe with a jquery plugin) (completed)


still need to work on for full proposed functionality:

-Table sorting the date Watched column needs to be fixed (completed)
-Added full functionality for the Delete Button, fix the fact it needs a page refresh to take away the table row (completed)
-add validation to submit review button.  If no review or date watched is entered, don't submit.  (completed)


Phase 3  (functionality passed what I proposed for this capstone project): 
This phase will be to add a social aspect to the reviews.  
I am thinking of having it where when I write a review it will either post a facebook status to check out this 
review or I will push this review to a facebook note and update mystatus to read the review.

update 3/20/13:

-In order to make these review more accessable to social network users I will move away from TwitterBootStrap popover to 
hold the review submitted (completed)

-I will make the submitted reviews display in a hidden div, so that when you click on the title of the movie in the table (completed)
it will show the hidden div with the submitted review and the movie info cards that are displayed in the form. (completed)
-have hidden <tr> sort (through table sort) with the visable <tr>

update 3/21/13: 
New strategy to display movie review from table:

-scale the movie review table to half the size and float it left on the page
-Have a div, floated right (next to movie review table) that will append the movie info and review when a title is clicked on the table

This approach should make it easier to sort the table and to share the review through social networks

	


