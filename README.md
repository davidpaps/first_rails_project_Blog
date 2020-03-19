# Blog App (using Ruby on Rails)

Ahead of our second 2-week project at Makers, I made this basic blog app in order to try and get to grips more with the Ruby on Rails framework. I had spent 5 weeks using the Ruby programming language before this week, but I has never come across this framework. Since the next 2 weeks are going to be focused on using this tech, i thought I would explore some of the features and syntaxes to get a jump start on the Facebook project.

I found Rails to be strange at first, but after some playing around, very efficient and time saving. It seems to do lots for you (database migration, setting up tables, creating paths for era files etc), that before I was doing manual. I see the method in the madness, as it is good to know what is going behind the scenes when using the Rails commands.

The app is extremely basic, but includes many important functions that are good to know. A user can create a post, they can then show, update and delete the post (completing the CRUD cycle). Although there is no CSS, I am very happy with my first rails project, including important functionality that i know will come in useful in the future.

---

## How to Run

Clone this repo, and from the command line visit this directory. Then type:

```
bundle install
bin/rails db:create
bin/rails db:migrate
```

This will install the dependancies, and then create and update the database to store the posts. To run the tests, type:

```
bundle exec rspec
```

To run the app in the browser, you will need to launch the server, type:

```
rails server
```

And visit [*localhost:3000*] (http://localhost:3000/) to start using the app!
