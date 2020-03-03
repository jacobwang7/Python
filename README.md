# Python

Random characters 
You decide to create a program characters.py that fills a two-dimensional list with random symbols, and then performs 
some operations on it. Create a grid with 5 rows and 4 columns. You then write four helper functions: fill_grid(g) which fills grid with 
random symbols, print_grid(g) which prints grid, count(g, s) which counts how many times a symbol occurs, replace(g, s1, s2) which replaces
one symbol with another. Your main function asks the user for the symbol to count and the one to replace it with, and displays the grid
at each step.

Movie actors
As a fan of golden age movies, you decide to write a program movies.py that can retrieve the movies that various actors 
starred in together.  To do so, you create a dictionary with the actors’ names as keys (stored as tuples) and the movies as values
(stored as lists), which you store in a global variable at the top of the file: movies = {('Hepburn', 'Audrey'):['Roman Holiday', 
'Sabrina', 'Funny Face', 'Love in the Afternoon', 'Green Mansions', "Breakfast at Tiffany’s",'Charade', 'My Fair Lady'], ('Grant', 'Cary'):
['Bringing up Baby', 'Holiday', 'His Girl Friday', 'An Affair to Remember','The Philadelphia Story', 'Arsenic and Old Lace', 'North by 
Northwest', 'Charade'],('Tracy', 'Spencer'):['Woman of the Year', 'Thirty Seconds Over Tokyo','State of the Union', 'Adam’s Rib', 'Father
of the Bride',"Father’s Little Dividend", "Guess Who's Coming to Dinner", 'Desk Set'], ('Hepburn', 'Katherine'):['Holiday','Desk Set', 
'The Philadelphia Story', 'Woman of the Year', "Adam's Rib",'State of the Union', 'Bringing up Baby', "Guess Who's Coming to Dinner”]}
Next, you create two functions, print_database(), that prints the movies by actor, and print_common_movies(actor1, actor2) that prints 
the movies that both actors starred in, and raises a KeyError exception if an actor’s name does not occur in the database.  The main 
function asks the user what task to perform, and if a query, the names of the two actors. 

Sorting cards 
You decide to create a program suits.py to tally and sort the cards in a hand.  You include your earlier functions 
pick_cards(n) and print_cards(h), plus four new ones: tally(h), which creates and returns a dictionary with suit as key and count 
as value, sort_cards(h) which creates and returns a dictionary with suit as key and a list of the face values as value, print_tally(t),
which prints the tally, and print_sorted(s), which prints the cards in each suit. 
