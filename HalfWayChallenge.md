# Half Way Challenge

1. What is a class?

A class is a model. It is how we define types of objects.


2. What is an attribute?

An attribute is a characteristic that an object can have. They are defined by a key and objects have a value for each attribute key.

3. What is an object?

An object is an instance of a class.

4. What type of object is a PORO?

It's a plain ole' ruby object.

5. What is a Rails model?

It is an Active Record class.

6. What is your absolute favorite meal?

Eating other programmers for breakfast.

7. What is the difference between a locally scoped variable and an instance variable?

Locally scoped vars can only be accessed by the method to which they are scoped. The scope of an instance variable is the class where it's defined.

8. Why do we use version control like git?

So we can access previous commits.

9. What is the difference between git and GitHub?

our git is a local db. We push our favorite commits to GitHub, a remote database.

10. What is your ideal vacation?

Salmon fishing in Alaska.

11. What does the pattern of Separation of Concerns mean and why do we use it?

It means that we give each model very little functionality. We do not want overlapping functionality because that messes up al of our organization and does not follow the object-oriented idea.

12. What does the pattern MVC mean?

model-view-controller

13. What is the difference between a Rails model and a database table? What is their relationship?

A rails model contains methods. A db table contains a model's attributes and their types.
Each model has one database table.

14. How do we modify the database for our Rails app?

migrations

15. What do you do to relax?

Read reddit, watch netflix with gf.

16. What is a gem and how do we use them in our Rails apps?

A gem is external functionality that a rails app does not contain. We add a gem to our gemfile.

17. In what part of a Rails application do we tell it how to handle an HTTP request to a specific path, like: `http://localhost:3000/movies`?

routes.rb



18. In what part of a Rails application do we hold data provided by the user, in order to use it, save it to the database, or retrieve it from the database?

a storage directory

19. In what part of a Rails application do we render data, in HTML, to present to the user?

views

20. What TV show do you never want to miss?

Better Call Saul

21. What part of a Rails application processes actions, uses models, and directs flow to the proper view?

controllers

22. If your app gave you the following error message, on this line of code, what would it indicate?


        undefined method `downcase' for nil:NilClass


        <%= user.name.downcase %>

the .name call was not processed correctly, the name attr might not be accessible or might not exist

23. What gem did we use to paginate our Collections?

kaminari

24. What gem did we use to provide upload functionality?

carrierwave

25. What is your favorite musical artist or group?

Hm... very tough.

Alt Rock: RHCP or Sublime
Electronic: Laxx or Bassnectar
Rap: Tech N9ne

26. What technology do we use to style HTML in the browser?

css

27. What type of view templates have we been using in our class to create dynamic HTML?

erb

28. What type of helpers do we use to check data against certain rules and requirements before it is saved to our database?

require

29. What are model associations?

relationships between our models such as has_many and belongs_to

30. Based on the name, if The Iron Yard wasn't a code school, what else might it be?

definitely a gym

31. What code would you use to find the a User record in the database with an id of 17?

User.find(17)

32. If you want to use an image inside your app, in what directory do you put it?

assets/images

33. What helper do you use to create a form to edit or create a specific resource?

form_tag

34. What does this mean? `||=`

it's memoization. it catches the results of a method the first time you run it, and reuses it without recalculating the results.

35. What is your nickname? If you don't have one, what do you wish it was?

Ryan

Not-So-Slim Shady

36. What is a scope? Please provide one example.

it is the range that has access to a variable.

A regular model's scope is it's class.

37. What is _rake_? Give some examples of how and when we use it?

It is a ruby asset that collects tasks and is able to execute them

rake name_space:task
rake db:create

we use it in the command line mostly for running tasks that help development

38. How do you deploy your app to Heroku?

we create a heroku app with 'heroku create', and git push heroku master

39. What gem can we use to provide a fast, yet custom and robust, administrative section for our apps?

active admin

40. What is does _anopisthographic_ mean?

paper with writing on one side????

41. If a User has many ParkingTickets, and the `user` variable points to a User object, what code would you use to get all the ParkingTickets?

user.parkingtickets.all

42. If an Address model has a postal code attribute, what code would you use to get all Addresses from the database with a postal code of _33771_?

scope :StPete3, -> {where(postcode: 33771)}

43. How do you create a new Book object in the database, if a Book class has the following required attributes: title, author, publish_year, pages?

Book.create(title: '50 Shades of Heyyyy', author: 'horny lady', year: '19dickety2', pages: '4')

44. If we get this message in our log after attempting to save an object, what does it mean?

We have a params permit statement without 'first_name'
        Unpermitted parameters: first_name


45. What one question do you wish I would have asked?

Are you caught up yet? HELL YES I AM
