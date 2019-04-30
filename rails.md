###### 1. What command will create a new Rails application?

```
rails new <app_name>
```
###### 2. What optional flag will set the database to Postgres?
```
--database=postgresql
```
###### 3. What Rails 5 command will create the application's database?
```
rails db:create
```
###### 4. What command will run the Rails scaffold generator?
```
rails g scaffold <Scaffold Name>
```
###### 5. What controller process allows for a method to be run before other controller methods?
```
before_action :<method name>
```
###### 6. What does the index action in Rails typically do?
Lists out multiple records for the corresponding controller.
###### 7. What routes are included in the resources method?
- index
- new
- create
- show
- edit
- update
- destroy
###### 8. What command lists all defined routes in application?
```
rake routes
```
###### 9.What happens when you place an instance variable in a controller method?
The data inside is available to its corresponding view.
###### 10. What's the difference between the new and create methods?
New instantiates the object, create communicates with the model.
###### 11. What's the naming convention in Rails between view files and controller actions?
For the default process to take place, the controller action name needs to be the same as the view file.
