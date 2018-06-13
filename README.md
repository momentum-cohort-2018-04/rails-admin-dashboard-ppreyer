# Admin Dashboard for Beer Tracking App

I decided to add ActiveAdmin to my Beer Tracking API application. The dashboard consists of a homepage, a page with a list of every beer, and a page with a list of every note taken on each beer. The homepage is a snapshot of the data in the beers model with various aggregation charts. The dashboard has the ability to perform CRUD actions on both beers and notes. 

I spent most of my time working on the homepage and implementing the Chartkick gem to enable charts. I was able to get perform limited queries to create basic charts, but I'd like to learn more about how querying / sorting data works with DSL in the active_admin.rb file.

## Homepage
![screen shot 2018-06-12 at 10 38 29 pm](https://user-images.githubusercontent.com/1817873/41327720-8176b8f0-6e92-11e8-9de6-8b1c436922e3.png)

## Beer Page
![screen shot 2018-06-12 at 10 38 40 pm](https://user-images.githubusercontent.com/1817873/41327719-81637f56-6e92-11e8-8466-6a7d1d6f9925.png)

## Note Page
![screen shot 2018-06-12 at 10 38 53 pm](https://user-images.githubusercontent.com/1817873/41327718-812068d8-6e92-11e8-8f67-d810b4996333.png)




# Adding an Admin Dashboard

Using either ActiveAdmin or Administrate, add an admin dashboard to any previous application you've built in class.

The dashboard should let admin users manage the data of your application in a UI.

For the first step of this assignment, design the admin dashboard. What do you want your admin users to be able to do?
When you know what your project specs are, implement the dashboard.

Your homework submission should be a README explaining what you decided to do, including a link to the project repo that you added the admin dashboard to. Please also include a screenshot of the admin dashboard main page to illustrate your README.
