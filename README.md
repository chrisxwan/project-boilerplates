# CS213 Project Boilerplates

For those of you who want to use some boilerplates for your CS213 project, here are some that aren't too difficult to get started with. These boilerplates are written in different frameworks and languages, so feel free to use the one you're most comfortable with. I will list them in order of usability and personal preference.

## Flask Boilerplate
For those of you who took CS50 / enjoy Python, this is definitely the boilerplate to use. I really think it's amazing (:

The template is called [cookecutter](https://github.com/sloria/cookiecutter-flask)

Basically, just visit the link above and follow the first two instructions:
```
pip install cookiecutter
cookiecutter https://github.com/sloria/cookiecutter-flask.git
```

That will create a directory in your current directory. This directory will be named whatever you specified according to the questions asked you. After that, cd into your director and take a look at the README. Follow the instructions in the README to set up your application.

This starter code is really nice because it's lightweight, and you get set up with a SQL database and BootStrap. It's also the one I'm most familiar with, so if you have any questions, you can feel free to ask me (:

## Meteor Boilerplate
Meteor is a Javascript framework -- I've actually never used Meteor before, but from what I've heard, it has a really low learning curve, especially compared to other Javascript frameworks like Express and Hapi. The boilerplate that I would recommend using is [Orion](https://github.com/matteodem/meteor-boilerplate/blob/master/GUIDE.md). 

Basically, just follow the instructions in the guide. The only instruction that may go wrong is when you are asked to do:

`orion create appName`

There's a chance that your computer will complain that the `orion` command is not found. If this is the case, you will want to find where orion was installed from `npm install`. Suppose Orion was installed in /x/y/z/orion. You will want to run this command in your command line if you're on a Mac / Linux machine:

`export PATH='/x/y/z:$PATH`

Then, you should be able to run `orion` from the command line.

Orion is really nice because it gives you flexibility to create your own models + integrate with a database.

## Express Boilerplate
Unfortunately, most Express boilerplates are pretty large (Express is more widely used to create large-scale applications). I found two pretty lightweight ones that aren't too terrible to use:

(1) [Express Application Generator](https://expressjs.com/en/starter/generator.html). The instructions are pretty straightforward. The only thing that isn't amazing about this is that it doesn't come with any Database support, and the templating engine it uses is Pug (I would recommend using Handlebars)

(1) [Clementine](http://www.clementinejs.com/versions/standard.html). This is a really tiny boilerplate, and it doesn't really set up THAT much for you, but it DOES give you Database support with [MongoDB](https://docs.mongodb.com/manual/tutorial/install-mongodb-on-os-x/). MongoDB is a type of database that is reaaaaalllyyyyyy easy to get started using. You can follow that link to install MongoDB on whatever machine you're on and get started with it really quickly.

## Sinatra Boilerplate
Sinatra is a lightweight Ruby framework. However, I would highly not recommend that you use this unless you love Ruby / are REALLY interested in learning Ruby. The boilerplate is [here](https://github.com/neverstopbuilding/sinatra-boilerplate).

Basically, you'll just want to follow the "Making it your own" instructions. One note: your Ruby version needs to be >= 2.2.0. I ran into a lot of problems because I was using 2.0.0. 

This boilerplate doesn't come with a database, but it comes with a nice testing framework.

## Questions?
I have gotten all four of these boilerplates up and running, so if you need help getting started, please don't hesitate to email me at christopher.wan@yale.edu.

As mentioned, I don't know much about Meteor / Sinatra. I imagine I could still answer questions about Meteor, but for Sinatra, Google might be your best resource.

For Flask, I have a decent amount of experience, and for Express, less so, but still fell free to ask.