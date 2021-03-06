# Game Simulation
 
## Instructions to run the project

Open the game_simulation.html using any common explorer (Google Chrome, Firefox, etc).

Then you will see a simulation panel with the following functions:

### `Number of briefcases to choose from:`

To choose how many briefcases a contestant will be choosing from (this will be 3 by default according to the requirement).

And this is a parameter to toggle that I think will be useful although not required in the handout.

### `User chance to switch:`

After the host eliminates the briefcase(s), what percentage of the contestants will choose to switch? This can be 30%, 20%, 50%, etc. So I provide the API to choose this percentage to allow various settings of the simulation.

### `Whether the host knows the answer:`

Whether the host knows the answer will affect how the host eliminates the briefcase(s) since the host could reveal the winning briefcase by accident if the host does NOT know which one of the briefcases contains the prize. So I provide the API to set whether the host knows the answer and allows various settings of the simulation.

## start simulation!

After setting all the parameters, we click the "start simulation!" button to run the simulation.

The number of prizes given during the simulation will be shown to give a quick impression of whether or not we are giving too many prizes.

Then users could choose to download a CSV file containing detailed information about the simulation:

### `Detailed information of the simulation in the generated CSV file:`

Number of briefcases to choose from: how many briefcases a contestant will be choosing from (this will be 3 by default according to the requirement)

The host knows the answer: whether the host knows the answer of the winning briefcase

The user switches the choice (for each round): whether the contestant chooses to switch the choice in this round

The case chose (for each round): the # of the briefcase chosen by the contestant

Case contains the prize (for each round): the # of the briefcase containing the prize. 

Win/Fail (for each round): whether this round is a win/fail

Win by accident (for each round): whether the contestant win by accident (host reveals the prize).
