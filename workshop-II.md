# Puppy Bowl Test Suite

## Unit testing

### Main Page

- Expect the players to be in a formatted list
- Expect each player to have two buttons: A "See details" button and a "Remove" button
- Expect the "See details" button to show the player's name, breed, and assigned team(or "unassigned" if they do not have a team)
- Expect the "See details" button to show a larger version of the picture
- Expect the "See details" button to have a button to return to the main list
- Expect a dropdown so users can change the team assignment for the current player
- Expect the team assignemnt to change immediately(without refreshing the page) when using the dropdown
- Expect a filter that shows all of the teammates as the current player


### Adding and Removing Player(s)

- Expect a form on the page that allows us to add a new player
- Expect the form to have two inputs and a button: one input for the player name, one input for the player's breed, and a submit button
- Expect the submit button to send the data and add the player to the roster
- Expect the form to have an additional input that allows users to provide an image URL
- Expect the the new player to be in the roster without refreshing the page
- Expect the player to be removed from the list without a page refresh
- Expect the submission to fail if the user did not input one of the fields
- Expect the submission to fail of the name is already taken


## Integration

- When submitting the form, the player is added to the list without refreshing the page
- When adding a player, the linked image shows up as the player portrait


## Functional

- As a user, I can submit a form and have my player be added to the list without refreshing.