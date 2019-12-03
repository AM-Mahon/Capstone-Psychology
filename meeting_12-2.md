# 12-2 meeting

## Muenzinger E317, 5:30 pm

## In attendance

- Kakam Chen
- Ann Marie Mahon
- Alex Sandridge

## Topics covered and decisions made

### Tasks

- Learning task
  - Tell user we have x people, person one is John, 2 Bob, etc.  Then ask which face is "Bob".  This task has no associated questions, just introducing names and faces for the day.  One face/name pair per page.
- Training/practice tasks
  - Name + face
    - Here's a name, which face is that (multiple choice)
  - Who's new
    - Here are x+1 faces, which one have you not seen before (in the learning task).  Like test "choose which is NOT true"
  - Memory
    - Card game, there are duplicates of each face, flip over the two that are the same.  May or may not show an initial state of all cards face up.
  - Shuffle
    - Given initial state of faces in order, next page is faces out of order.  Task is to reorder correctly.
- Assessment tasks (new user first activity, not daily first)
  - These tasks do not use the faces presented in the learning task
  - Forced choice
    - Given one face, then next page a set of faces.  Select which one you just saw
  - Encode-Recognition
    - Dropped
  - Same-different (takes many trials)
    - Given a face, then next page say whether or not that's what you just saw (fixation cross -> face a -> mask -> set of faces)
- Focus on quality over quantity with tasks.  More is great, but one in each bin is totally workable
- Learning task is must, training next, assessment *can* be done in lab only but integrated would be good.  Really really need training task
- Preference towards small assessment daily (forced choice or same-different), large assessment using Same-different at end of week/level

### Server

- We do not need to set up anything
- Just need to decide how we want to do it
- Current is JATOS (not similar to what we need to do)
- Important is results of assessment, item by item.  If we can get item by item for training great, not required.
- Can look into Heroku, AWS, etc.  Determine what is cheapest/most convenient

### High level

- Not really like duolingo, memorization of specific faces is not the goal, instead reduction of CRD is
- There will be difficulty pools, repetition of faces for just one day is ok.
- We focus on the infrastructure of the app, Psych team focuses on the stimuli (faces) we just put them in the app.

### Priorities

1. Learning task
2. Training task (Name + Face first)
3. Assessment task (either forced choice or same-different)
4. Then more training (memory, shuffle, who's new last)
