### [Makers Academy](http://www.makersacademy.com) - Week 8 & 9 Group Programming Project

Acebook - Team Luckerberg
-

[![Build Status](https://travis-ci.org/Hyan18/acebook-luckerberg.svg?branch=master)](https://travis-ci.org/Hyan18/acebook-luckerberg)
[![Maintainability](https://api.codeclimate.com/v1/badges/a99a88d28ad37a79dbf6/maintainability)](https://codeclimate.com/github/codeclimate/codeclimate/maintainability)
[![Test Coverage](https://api.codeclimate.com/v1/badges/a99a88d28ad37a79dbf6/test_coverage)](https://codeclimate.com/github/codeclimate/codeclimate/test_coverage)

## Team members
- [Dawid Szpener](https://github.com/DawidSzpener)
- [Ben Sheridan-Edwards](https://github.com/BenSheridanEdwards)
- [Eve Noirault](https://github.com/even13)
- [Harrison Yan](https://github.com/Hyan18/)
- [Julie Cheng](https://github.com/jj49411)

## App and card wall
1. Find our Acebook app [here](https://acebook-luckerberg.herokuapp.com/).

[You can find the engineering project outline here.](https://github.com/makersacademy/course/tree/master/engineering_projects/rails)

2. Our trello board is [here](https://trello.com/b/0LloZrOg/acebook-luckerberg).

3. Learning wiki is [here](https://github.com/Hyan18/acebook-luckerberg/blob/master/learning-wiki.md)

## User stories  
```
As a User  
So I can use Acebook  
I want to sign up.  
```  
```
As a User
So I can come back to Acebook  
I want to log in.  
```  
```
As a User  
So I can leave Acebook safely 
I want to be able to log out.
```

```
As a User
So I can keep track of posts
I want to see posts on my page.
```

```
As a User
So I can share my ideas
I want to be able to write new posts.
```

```
As a User 
So I can cange my mind about what I post
I want to be able to edit and delete my own posts.
```

```
As a User
So I can see posts on my wall
I want to have my own wall.
```

```
As a User
So I don't waste time
I want to see my wall directly when I log in.
```

```
As a User
So I can share ideas
I want to be able to publish posts on people's walls as well as my own.
```

```
As a User
So I can give my opinion
I want to leave comments on posts.
```


## How to install and run

First, clone this repository. Then:

```bash
> bundle install
> bin/rails db:create
> bin/rails db:migrate

> bundle exec rspec # Run the tests to ensure it works
> bin/rails server # Start the server at localhost:3000
```
## How to run tests
```bash
> rspec # Run the tests
> rubocop # Check code quality
```
## Versioning
Acebook uses ruby version 2.5.0p0. To change ruby versions run
```rvm install ruby-2.5.0p0``` in the terminal.

## <a name="Features">Features of MakersBnb</a>

### Sign Up

##### Users can sign up to Acebook:
![](https://github.com/BenSheridanEdwards/Makers_Acebook/blob/master/images/Acebook-Sign-Up.png)

### Log In

##### Users can log in to Acebook if they have an account:
![](https://github.com/BenSheridanEdwards/Makers_Acebook/blob/master/images/Acebook-Log-in.png)

### Your own Wall

##### Upon signing in, users are redirected to their wall, where the user can post messages on their wall for others to see:

![](https://github.com/BenSheridanEdwards/Makers_Acebook/blob/master/images/Acebook-Bens-Wall.png)

### Finding other Users

##### Clicking on the users tab on the navigation bar directs you to a list of active users:

![](https://github.com/BenSheridanEdwards/Makers_Acebook/blob/master/images/Acebook-List-Of-Users.png)

### Seeing other Users' Walls

##### User's can see other users walls, and everything they've posted on there

![](https://github.com/BenSheridanEdwards/Makers_Acebook/blob/master/images/Acebook-Julies-Wall.png)

### Users can also post on each others walls:

![](https://github.com/BenSheridanEdwards/Makers_Acebook/blob/master/images/Acebook-Julie%26Ben-Post-On-Julies-Wall.png)

### Commenting

##### Users can comment on their posts:

![](https://github.com/BenSheridanEdwards/Makers_Acebook/blob/master/images/Acebook-Ben-Add-Comments.png)

##### And users can comment of others posts:

![](https://github.com/BenSheridanEdwards/Makers_Acebook/blob/master/images/Acebook-JoinedImage-Julie-Wall-Posts-And-Comment.jpeg)

### Editing and Deleting

##### Users can edit and delete their posts and comments within 10 minutes of originally posting them:

![](https://github.com/BenSheridanEdwards/Makers_Acebook/blob/master/images/Acebook-Ben-Can-Delete-His-Post-Within-10-Minutes.png)

### Seeing all posts

##### Every user can also see all the posts ever made, on the posts page: 

![](https://github.com/BenSheridanEdwards/Makers_Acebook/blob/master/images/Acebook-Julie-All-Posts.png)


