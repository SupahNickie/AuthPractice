October 15, 2013

User Authentication Practice

- Based on Railscast 250, this app is just a quick and dirty proof of concept learning exercise for me to see how to create authentication in Rails from scratch. The proper sessions are created and users are stored in the database, but there is no authorization backing any of the posts, meaning that anybody can edit the resources available to the user, which would be the articles for a blog in this case. Also missing are data validations beyond simple "presence of" and "uniqueness of", so many types of non-valid form submissions are accepted.
