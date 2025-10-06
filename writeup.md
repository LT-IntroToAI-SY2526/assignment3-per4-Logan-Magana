# Assignment 3 - Write UP

## Description
This assignment completes our movie chatbot system by implementing action functions that query our movie database and building a natural language interface. You implemented functions to search for movies by year, director, and actors, as well as the core search system that matches user queries to appropriate database operations. This builds directly on the pattern matching work from Assignment 2 to create a functional conversational AI system.

## What to complete
1. Complete all action functions in `a3.py` (title_by_year, title_by_year_range, etc.)
2. Implement the `search_pa_list` function to handle pattern matching and responses  
3. Add at least one new movie to the database with proper formatting
4. Create a new pattern/action pair and add it to the pa_list
5. Ensure all provided assert statements pass
6. Complete the reflection questions below
7. Push your code to github for grading

## Reflection Questions

1. What are some key programming concepts or techniques that you learned while completing this assignment?
 Some main concepts I learned from this assignment was indexing ( the [0] and [1] ) and the extend function that was used for the actor_by_director function. I also used for loops and if statements throughout the program.


2. How does the overall movie chatbot system work? Explain the flow from when a user types a query to when they receive an answer.
 The process begins with the user typing in a question. The program will take that response and put it through the match function, which will determine what function will be used later on. Based on the matches with keywords (like asking for movies in 1977) and then uses the function that corresponds to that (like title_by_year) to continue the process. This function will connect with the movie data base and will loop through the list to find a match that meets the functions conditions ( like the lists that have movies that contain a specific year) and appends what the user was asking to the result, which is what is printed.



3. What are some real-world applications where this type of pattern-matching chatbot system could be useful? How might you extend or improve this system for practical use?
 This is basically the mini/beta version of the ai chatbots that are used currently like chatGPT. By expanding the database to include more than just movies, as well as adding more functions. You would get to a version of a google search. For my personal use, It would probably be something as just adding a similar database (like videogames) and tweaking some of the functions so that it could work.