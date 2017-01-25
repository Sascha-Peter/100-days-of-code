# 100 Days Of Code - Log

### Day 1: January 7, 2017

**Today's Progress**: 
* Creation of the base project and default files which are required
* Adding the dynamic secret key generation (inspired by OpenShift)

**Thoughts:** 
The set up of the template project will increase the speed in which I'll be able
to deliver django projects in the future and help out with the other pet projects
I'll be tackling during those 100 days.

**Link to work:** [Django Project Template](https://github.com/Sascha-Peter/django-project-template)

### Day 2: January 9, 2017

**Today's Progress**: 
* Creation of base template files (base, nav, footer)
* Added base authentication system with url overwrite to prettify the urls
* Added bootstrap support

**Thoughts:** 
With the base html templates in place and bootstrap added in, I'll be easily able
to create new base templates with ease and have the relevant building blocks in place
to get going from the beginning.

Using django's own authentication system will save me hassle and stress with writing my
own and the prettification of the urls for password reset go well along with the rest
of the url structure I have in mind or my future pet projects.

**Link to work:** [Django Project Template](https://github.com/Sascha-Peter/django-project-template)

### Day 3: January 10, 2017

**Today's Progress**: 
* Creation of cookiecutter template
* Adjustment of the project to make use of the cookiecutter parameters

**Thoughts:** 
I've heard about cookiecutter ages ago but didn't use it myself. Now as I've re-discovered it
and confirmed that I'm about as smarty pants as a few thousand developers who already done an
impressive and comprehensive django-template for cookie cutter, I'm even more happy about finishing
this project :D I'll re-invent the wheel but for my own needs. I might actually do a cookiecutter
django template for OpenShift, which is quite a bit different from a regular django setup. We will see.

**Link to work:** [Django Project Template](https://github.com/Sascha-Peter/django-project-template)

### Day 4: January 11, 2017

**Today's Progress**: 
* Change cookie cutter project structure

**Thoughts:** 
There's been a few issues around the cookie cutter usage which made me look into some of the 
example cookie cutter templates other people have been doing and I've found that there was an issue
with my folder structure. I'm still debugging it as I've not completely resolved it but hope to get that
done in the next session.

**Link to work:** [Django Project Template](https://github.com/Sascha-Peter/django-project-template)

### Day 5: January 14, 2017

**Today's Progress**: 
* Adjusted the django templates not to contain conflicting jinja2 syntax
* Set correct paths in the settings file
* Made the cookiecutter template work

**Thoughts:** 
Jinja2 is a pain in the butt and I'd refrain from using it in conjunction with django projects. 
Unfortunately, cookiecutter installs jinja2 as it uses it itself. I'm sure there is a way around
but it's quite late and I'm too tired to look into that now - also spend the time I allocated for
the project today already.

**Link to work:** [Django Project Template](https://github.com/Sascha-Peter/django-project-template)

### Day 6: January 15, 2017

**Today's Progress**: 
* Set up the quickstart of django-restframework
* Read part of the documentation

**Thoughts:** 
Having worked with Django for over 5 years before, I always had the feeling that flask was very crafty. 
The work with flask over the last year was a very good learning experience and I learned a bit more about the
odds and ends of what a framework needs - but then again, I also learned to much more appreciate the 
"magic" which django gives you out of the box. The tidious repetitive tasks which you don't have to hand-write
and just go ahead with your code on which you can focus. 

Now looking at django-restframework, I feel even more so like we've been wasting so much time re-doing the same 
settings over and over again. Cookiecutter was the first step into the right direction of cutting away tidious
setup time and django restframework is the next step of going away from re-doing the same stuff in flask over
and over again - but in django.

**Link to work:** [Django RESTframework test](https://github.com/Sascha-Peter/django-restframework-test)

### Day 7: January 23, 2017

**Today's Progress**: 
* Complete chapter 1 of the Django RESTframework tutorial - Serializing

**Thoughts:** 
Coming from a django background, things are pretty familiar in the way how the django rest framework is handling
it's implementation and notation. Instead of forms you have views with serializers, you call the JSON renderers
instead of the render function of templates, etc. 

I think there is a lot which can be done in very little time in comparison of having to set up a flask app, unless cookie
cutter is involved and you have all your building blocks ready to add-on / install as pip packages.

**Link to work:** [Django RESTframework test](https://github.com/Sascha-Peter/django-restframework-test)

### Day 8: January 24, 2017

**Today's Progress**: 
* Complete chapter 2 and half of chapter 3 of the tutorial on Django RESTFramework

**Thoughts:** 
Now it starts looking and feeling like a django app :D Built in error codes, request/response objects which you can
manipulate and fill in, built-in admin panel which incorporates your doc strings into the api documentation, automated
form for posting and deleting things on the API in the docs itself, very django'esk :D Next things will be middleware
and other fun topics, can't wait!

If we'd do django restframework at work we'd save so much time. I'll make sure that it will be put onto the radar of 
management.

**Link to work:** [Django RESTframework test](https://github.com/Sascha-Peter/django-restframework-test)

### Day 9: January 25, 2017

**Today's Progress**: 
* Complete chapter 3 of the django restframework tutorial

**Thoughts:** 
Class based view which provides get/put/delete functionality on a restful resource done in 6 lines.
Yep, we're definitely doing Django right now :D 
So much built in just as I was used to from django itself. Much pre-build, such convenience, wow. ;)
Definitely implementing some of my pet projects in Django RESTFramework instead of using flask. 

**Link to work:** [Django RESTframework test](https://github.com/Sascha-Peter/django-restframework-test)
