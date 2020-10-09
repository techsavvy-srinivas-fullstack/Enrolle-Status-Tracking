# Enrolle-Status-Tracking
This is a MicroService for tracking the status of enrolles in a health care program

Following are the api urls as part of the application

dependent apis

Type: Get
requestUrl :localhost:8080/enrolles/user/{userId}/dependents
Description:To get all users


Type: Post
requestUrl :localhost:8080/enrolles/user/{userId}/dependent
Description:To save dependents for user


Type: Put
requestUrl :localhost:8080/enrolles/user/{userId}/dependent/{dependentId}
Description:To update dependents for user

Type: Delete
requestUrl :localhost:8080/enrolles/user/delete/{userId}/{dependentId}
Description:To delete dependents for user



user apis

Type: Get
requestUrl :localhost:8080/enrolles/users
Description:To get AllUsers

Type: Post
requestUrl :localhost:8080/enrolles/addUser
Description:To Save user

Type: Put
requestUrl :localhost:8080/enrolles/user/{id}
Description:To Update user

Type: Get
requestUrl :localhost:8080/enrolles/user/{userId}
Description:To get user details


Type: Delete
requestUrl :localhost:8080/enrolles/delete/{userId}
Description:To Delete a particular user
