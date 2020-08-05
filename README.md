# MWA - Homework 13 - Angular 03
## Coding Exercise
* Your main `AppModule` has a service with two methods: 
  1. `getOnlineData()` that returns an array of JSON objects fetched from [https://randomuser.me/api/?results=10](https://randomuser.me/api/?results=10) and then save the results in `localStorage`. When App bootstrap, you should call `getOnlineData()` to fetch all the online data, stringify it, and save it into the `localStorage`. 
  2. `getCachedData()` that returns an observable with a JSON object read from `localStorage`.

  
* Create a featured module called `UsersModule` that has two components:
  1. `users` component, with `users` route, showing a list of users.
  2. `userdetails` component, with `users/:uuid` route, showing full details about the user.
* Both components will retrieve data from `AppModule` service.
* If a user tried to visit `users/:uuid` page without passing a correct `uuid` param, then your app must redirect them to a friendly error page. (use Guards).  
  
**Note: Write this exercise with Lazy Loading in mind.**

