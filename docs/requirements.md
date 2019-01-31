# Video Game Progression Requirements

## The Problem

Katie’s got a big problem... she buys way too many video games she knows she doesn’t have
time to play. But, you know how it is... they’re on sale... and she _must_ buy things on sale!
The real travesty is that she’s so busy programming @ Rangle that she never manages to beat
most games. She has a terrible habit of playing a new game and forgetting about the old
one all too quickly. And sometimes so much time has passed, she’ll have to replay games she
already started from the beginning just because she forgot everything! This is incredibly
inefficient, and her backlog of games to play is growing by the month!

Katie needs your help! She’s completely hopeless! She needs a way to catalog her games,
prioritize the games she wants to play most, and keep track of her completion to get caught
up. I will warn you, this journey may be a bit scary and unfamiliar - the road can be
quite tumultuous - but the situation is really quite dire and you're the only one who can help! Do you accept this grand quest?

## Requirements

- All code should be DRY and refactored
- Use @angular/ngrx for state management
  - State should only be placed in the module where it is used - avoid implementing all state
    at the root level
- Use feature-based, hierarchical folder/modules
  - Avoid root-level directories that contain every component and service at the root level.
  - Use componentization to separate concerns and ensure every component does only one
    concept
- Use lazy-loaded modules/features when routing
- All forms should display error messages per each field and disable the save button until the
  form is valid
- The site is designed with a screen size of 1366 x 768 in mind. Stick to this resolution.
  - You are not required to implement responsive behavior.
  - Use SASS to implement styles. Please do not use a tachyons-like library.
- Any corners of panes that appear rounded should be around 0.25 - 0.5rem (use your best judgement).

### Colors

- **Dark Blue:** #1e2e3b
- **Blue:** #30495f
- **Light Blue:** #9dafbd
- **Text on Dark Background:** #d6dbdf
- **Text on White Background:** #1e2e3b
- **Placeholder Text Color:** #6c6c6c
- **Menu Highlight:** #405e78
- **Green:** #76b43f
- **Light Green:** #a8ce87
- **Red:** #b43f3f
- **Light Red:** #c99898
- **Orange:** #b48c3f

### Sections

1. [App Layout](user-stories/01-app-layout.md)
2. [View Profile](user-stories/02-view-profile.md)
3. [Edit Profile](user-stories/03-edit-profile.md)
4. [Dashboard](user-stories/04-dashboard.md)
5. [Games Listing](user-stories/05-game-listing.md)
6. [Edit Game](user-stories/06-game-edit.md)
7. [Add Game](user-stories/07-game-add.md)
8. [Games Listing Filters](user-stories/08-games-filters.md)
