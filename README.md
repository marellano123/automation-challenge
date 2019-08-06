## Test automation coding challenge
Using mars-photos NASA open API - https://api.nasa.gov/api.html#MarsPhotos - create a pilot test framework from scratch.

### Notes
- Fork this repo and build the solution in *your* branch
- Coding the solution will be enough for passing the challenge.
- Any tools you add like log4j, cucumber, etc. will make your test framework look more awesome, and so do you.
- Any language can be used although we recommend Java since we have courses teaching Java :P


#### Test scenario #1
1. Get the first 10 Mars photos made by Curiosity rover on 1000 sol (Sol is the unit of tracking the date on the red planet)
2. Get the same 10 Mars photos made by Curiosity rover but on its equivalent earthling date
3. Compare images - Fail the test in case of any difference


#### Test scenario #2 (bonus)
1. Use NASA's API to determine how many pictures were made by each camera (Rover: Curiosity, Sol: 1000).
2. Compare amounts - Fail the test if any camera took ten times more images than any other
