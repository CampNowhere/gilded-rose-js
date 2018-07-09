# Gilded Rose JS Refactoring Exercise

I originally boosted this exercise from [here](https://github.com/emilybache/GildedRose-Refactoring-Kata) but I isolated JS and added my own instructions.

The exercise itself is simple: assume you are hired on to work as a game dev and are handed some terrible, unmaintainable code that governs item value depreciation in a new, totally awesome in-browser RPG. It is your task to do the following:

1. Read the specification document (GildedRoseRequirements.txt) to understand what it is the code should be doing.

2. Examine the inventory management system's source code (src/gilded_rose.js) and describe what is wrong with the code. (Bonus: figure out what sort of poor coding practice this is, there is a specific word for it.)

3. Refactor the code to correct the deficiencies you explained in step 2.

4. Add the requested feature per the specification document.

## Tips and hints:

* Basic github workflow: I have sent you a link to my copy of the repository. You can fork this repository to your own account. Then do a git clone to your machine from *your* fork of the repository. Make your changes in a separate branch. Then push the changes back to your github repo. Finally, open a pull request against my copy of the repo, comparing your feature branch against my master. Place all comments related to the changes either in your commit message or in your pull request.

* Write tests! There is a handy test harness included. If you run SpecRunner.html, it will give you a report of the results of all the tests specified in spec/gilded_rose_spec.js (including the example throwaway one). You can write all of your tests based on the spec document alone, and then run the test script to make sure your code works and you don't break anything.

* There is honestly no "right" answer, this is more of an open ended discussion so I can give advice where needed.
