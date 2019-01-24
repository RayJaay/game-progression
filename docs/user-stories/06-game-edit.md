# Edit Game

## Requirements

- Form Fields
- The number of hours played
  - Required and must a number >= 0
- The priority to finish the game, from 1 to 10 as selection list
  - Required
- A checkbox on whether they have beaten the game or not
- Form should display error messages per each field and disable the save button until the

## Details

- APIs Required:
  - `GET /games`: To retrieve the games current properties to as pre set form values
  - `GET /platforms`: To map platform ID's to display names on games cards
