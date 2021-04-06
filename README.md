# MWA - Homework 13 - Angular 03
## Coding Exercise
* Create a featured module called `UsersModule` that has one service and two components:
  1. Your service is provided at `root` and has a method `getData()` that returns an Observable with an array of JSON objects fetched from [https://randomuser.me/api/?results=10](https://randomuser.me/api/?results=10).
  2. `users` component, with `users` route, fetch the data using your service and display a list of users.
  3. `userdetails` component, with `users/:uuid` route, showing full details about the user. Data should be passed from the `users` component to `userdetails` component.
* If a user tried to visit `users/:uuid` route without passing a correct `uuid` param, then your app must redirect them to a friendly error page. (use Guards). A correct `uuid` code consists of the following format `155e77ee-ba6d-486f-95ce-0e0c0fb4b919`.
  
**Note: Write this exercise with Lazy Loading in mind.**

