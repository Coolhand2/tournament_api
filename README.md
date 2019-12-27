# Tournament Api

This API provides an interface for the UI to pull information from

## Cloud Formation

There may be a time we integrate with Cognito, Api Gateway, and Lambda, but for now we're just doing an ECS task as testing on Docker locally feels easier. We can utilize some environment variables to control endpoints in the UI. 


## Functions

- [ ] GET    /tournaments     - list all active tournaments
- [ ] GET    /tournament/{id} - show contents (players, matches) of given tournament id
- [ ] DELETE /tournament/{id} - delete tournament
- [ ] PUT    /tournament      - create a new tournament
- [ ] POST   /tournament      - update a tournament
