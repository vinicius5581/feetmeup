# FeetMeUp

App for personal trainers &amp; trainees 

- [ ] High Level Requirements
- [ ] APIs
  - [ ] Exercices
  - [ ] Routines
  - [ ] Sessions
- [ ] UI/UX
  - [ ] User Profile
  - [ ] Goals
  - [ ] Exercises
    - [ ] Exercise profile  
  - [ ] Routines
    - [ ] Routine profile
  - [ ] Reports
- [ ] App Connection
  - [ ] Nike
  - [ ] Fitbit
  - [ ] Garmin


## Users
### Groups
- Admin
- Manager
- Trainner
- Trainee 

### Privacy
Users profiles can be public or private

## Users relationship 
- Users can request to follow other users.
- A Trainee can have none, one or many Trainners. 
- A Trainner can have none, one or many Trainees.
- Relationships are iniated when a Trainne invites a Trainer or a Trainer invites a Trainne.
- Relationships are pending until the other party accepts it. 
- The relationship is stablheshed when a user accepts a request


## Exercises
- Should contain a label
- May contain a description
- May contain images
- May contain videos
- Privacy (Public, Limited, Private)

## Routines
A routine is a collection of exercises
- Should contain one or more exercises 
- Privacy (Public, Limited, Private)

## Sessions
- Should contain a start time
- Should contain an end time
- May contain exercices
- May contain routines
