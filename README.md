## Test automation coding challenge
Using mars-photos NASA open API - https://api.nasa.gov/api.html#MarsPhotos - create a pilot test framework from scratch.

### Notes
- Use standard tools and technologies.
- Coding the test will be enough for passing the challenge buuuut
- Any added tools will make your test framework look more awesome (e.g. log4j, cucumber, etc)


#### Test scenario #1
The purpose of this test is to check the images taken by Curiosity

1. Get the first 10 Mars photos made by Curiosity rover on 1000 sol (Sol is the unit of tracking the date on the red planet)
2. Get the same 10 Mars photos made by Curiosity rover but on its equivalent earthling date
3. Compare images - Fail the test in case of any difference
