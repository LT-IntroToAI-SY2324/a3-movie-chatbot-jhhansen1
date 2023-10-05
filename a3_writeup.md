# Assignment 3 - Writeup

Assignment 3 is all about creating this natural language query system.  In order to do so, you have to write a lot of functions to retrieve infomation.  You will also have to write a function to return answers from a pattern-action list.  There is a lot of work to accomplish in this assignment, but this portion is intended for you to write about what you accomplished.

## Reflection Questions
1. In your own words describe the `search_pa_list` function.
search_pa_list is a method that compares a list of strings input by the user to all of the strings in a list of tuples and once a match is found using the match function it returns the keyword of the question it is asking like the year or the movie name and then it uses the action in that tuple like title_by_year on the keyword to return the answer to the question. If there is no match it returns that it doesnt understand and if it finds a match but has no anwer to the question it returns no answer.

2. What movie did you add to the `movies.py` file?  What year was it made? Any specific reason you added that movie?
I added oceans 11 which was made in 2001. I added this movie because it is one of my all time favorites.

3. What pattern / action did you add to the paList data structure?  Why do you think that is a useful pattern / action?
I added what year was % made (atleast Im pretty sure I know I added one but it may have been a different one). I think this is useful because that is what I would type in to find when a movie was made so It will help provide answers for more formats of questions.

4. What is chatbot would you create that would be like this?  Describe why you would create it and what it would do.
I would like to create a chatbot with this style of code but with a database on 

5. What was the most difficult portion of this assignment?
figuring out how to start of search_pa_list was confusing for me epecially because pa_list was difficult to understand.

6. Did you write a new assert for your pattern action?



