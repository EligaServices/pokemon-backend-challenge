# Eliga Services Pokémon backend challenge

Welcome to the Eliga Services Pokémon backend challenge!

The aim of this code challenge is to test your backend capabilities in a fun, interesting way.

There's no time-limit on this task, and we won't be looking at git commits with time in mind. Everyone's busy, and we appreciate you taking the time to complete our task and fitting it around your other commitments.

The app is bootstrapped with the NextJS starter pack. You are free to use whichever packages or plugins you wish for things like styling, data-fetching, state-management etc.

## Overview

We'd like you to build an application that displays the first 151 Pokémon. Ideally, you'd be able to select a Pokémon and view its' image, description and stats. The layout, styling and user-features are up to you. This challenge is designed for you to show off and impress us with your execution, so have fun with it! You're free to incorporate as many flourishes (animation, etc), features (search, etc), and quality of life elements (testing, responsiveness), or as little as you wish.

### Notes
- You will need to use git for this challenge.
- Please commit only once for each step in the instructions.
- Do not bundle multiple steps in each commit.
- Please name each commit with the name of the appropriate stage, ie "Step 1".
- The Pokemon documentation is available here https://pokeapi.co/docs/v2.

**INSTRUCTIONS**

### Stage 1
- In `/pages/api.js` create a middleware function to receive the first 151 Pokémon from https://pokeapi.co/.

- The API returns a little too much data for each Pokémon than we'd like. We're only interested in the `name`, `id`, `stats` and `types` fields (as well as an image from the `sprites` object). Modify your middleware function to remove all other fields on each Pokémon and serve the reduced data to your application.

### Stage 2
Create a front-end to display all Pokémon by using the reduced data from your API function.

### Stage 3
Add some interactivity. Clicking on a Pokémon should show all the data for the selected Pokémon. You can display this however you like (modal, tab, etc).

### Stage 4
- Create a new api endoint in your Next.JS project, the endpoint needs to return the Pokémon evolution chain (in order) with all the base stats included for each evolution. Then display this data when the Pokémon is selected.

- Please refer to the swagger contract in `pokeAggrigator.yml` for the endpoint specifications, you can paste the contract into https://editor.swagger.io/ to view it in a nice UI.

## Submitting your work

To submit the challenge, either upload it to your Github and provide us access (preferred) or zip up the project (minus the node modules) and return it back to us via email.
