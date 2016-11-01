# Rails Chat App

A real-time chat app using web sockets and Redis and Devise for authentication. This was a project to brush up on the essentials of Rails after using Django for the past year. I also have done maintenence on already configured redis servers, but haven't ever set up my own. This project taught me how to do so. This project is deployed on Heroku.

In addition, I have never used Devise for authentication. At work, we authenticate only with JWT tokens, nothing else. I plan on adding in Google OAuth to the sign up options.

My goal with this project is to set up an application my company can use internally to provide feedback to our management team.

**Steps to get this running:**

(1) To install dependencies
```
bundle install
```

(2) To serve
```
rails server
```

Additional Features for the future:
- Google OAuth with Devise
- Accounts model, users are part of an account
- Better CSS, HTML - right now it looks awful, but focusing on backend right now
- Automatically create a new chat room every 2 weeks for all-hands
- Add an anonymous feature where users can choose to post chat room questions anonymously

