### List of Characters (Main Page)

- Display a grid/list of characters using the endpoint `/character`
- Must display the data from page number 5
- Each card must display:
    - Image of the character
    - Name
    - Species
    - Status (alive/dead/unknown) with visual indicator (colored dot)
- Have an option to navigate to a page with the character's details
- The table header must be color #008080
- Show the number of results at the top of the table and place two buttons next to it
    - The first button must increase the number of results
    - The second button must reset the number to the original value


### PLUS. Character Details (Individual Page)

- When clicking on a character, navigate to `/character/:id`
- Display all character information on a card; data items must have their own title (Name: Pepito):
    - Large image
    - Name, status, species, gender
    - Type (if applicable)
    - Origin (name and link if available)
    - Last known location
    - List of episodes where they appear (episode name)
- Technical details, the title item must be #006400 and the content #696969

API: https://rickandmortyapi.com/documentation