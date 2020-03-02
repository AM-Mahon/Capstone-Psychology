# 3-2 meeting

## Hangouts, 3:30pm

## In attendance

- Ann Marie Mahon
- Connor Dowd
- Alex Sandridge
- Kakam Chen

## Topics covered and decisions made

- Demo of current front end
- For shuffle
  - Order does not necessarily match the order of the learning task
  - Get subset in the proper order, then task is to put those back
  - Can scale with level
- Forced choice/who's new
  - 4 or 5 faces
  - Forced choice would NOT scale with levels
  - Who's new can, but the idea is face similarity is the scaling factor
  - Not tell the user how many faces are new?  Fixed or variable both ok.
- Forced choice/same different
  - It is easy to tell for same different if they are different
  - Use a 2 second "visual pattern mask", psych department has examples
  - Also shift the second face's position, multiple techniques are used
- Memory match
  - Scoring based on number of clicks, subtract from some number
  - It is ok for there to be the same number of faces between levels, but maybe scoring changes?
  - Implementing a timer for when all faces are visible would be good.  Also allows for scoring to be done based on time.
- Scoring
  - The important part is having the assessment tasks regularly and with a different set of faces, as that will allow for measuring improvement between levels
  - Training task scoring is for gamification and making the tasks feel more enjoyable/reinforcing for users.
  - Possibly have early version deployed to base scoring off of actual testing?  Could even just be a git repo that a research assistant clones and runs locally
- Levels
  - 8 faces per level is good
  - Only testing each face once seems ok, but maybe test again if you get a face wrong?  That would be a differentiator from current systems.  But no need to go through twice.
  - Who's new probably no multiple chances, as that introduces more considerations
  - Require passing levels (certain score) before moving to the next.  Scoring is then a more important question.
  - Learning task should be able to be redone whenever, regardless of performance
  - Optionally be able to do training tasks again.
  - Will check back regarding scoring and passing.
  - If users leave in the middle of a level, just do whatever is easiest.  Let them keep their place, restart, either is ok.
  - To pass the level pass each training task?  6/8?
- Feedback
  - If the user gets a question wrong, tell them that and tell them the correct answer

## Next meeting

Monday 3/16 3:30pm Hangouts
