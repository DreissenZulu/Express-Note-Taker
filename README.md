# Unit 11 Express Note Taker
Note taking application designed to write, save, and delete notes, written to and retrieved from a backend JSON file


## Approach
As the front end was already created, I needed to look at connecting this to the backend. I broke down the problem into smaller objectives:
1. Start a server using Express
2. Link the HTML to get and post requests in the backend JavaScript
3. Write the user's notes to the server's JSON file with unique IDs
4. The post method needs to write the note to the JSON and then return it to the user
5. Allow the user to retrieve a note by its ID and delete it if desired