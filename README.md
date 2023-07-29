## CHALLENGE 02 - Working with Middlewares

### Application middleware
- [X] checksExistsUserAccount
- [X] checksCreateTodosUserAvailability
- [X] checksTodoExists
- [X] findUserById

### Middleware Tests
- [X] Should be able to find user by username in header and pass it to request.user
- [X] Should not be able to find a non existing user by username in header
- [X] Should be able to let user create a new todo when it is in free plan and have less than ten todos
- [X] Should not be able to let user create a new todo when it is not Pro and already have ten todos
- [X] Should be able to let user create infinite new todos when is in Pro plan
- [X] Should be able to put user and todo in request when both exits
- [X] Should not be able to put user and todo in request when user does not exist
- [X] Should not be able to put user and todo in request when todo id is not uuid
- [X] Should not be able to put user and todo in request when todo does not exist
- [X] Should be able to find user by id route param and pass it to request.user
- [X] Should not be able to pass user to request.user when it does not exist
