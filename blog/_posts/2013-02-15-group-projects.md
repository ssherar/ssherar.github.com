---
layout: post
title: "Group Projects"
---

During the past Semester, I was tasked to make a solution with fellow students at my University. The project specification is a game for children/teenagers where they are able to fight, breed and sell monsters to gain as much money as possible, called Monster Mash. As I've had experience leading a team, I decided to put myself forward as the team leader (which I soon regretted...)

The tools we used were:

* Java with J2EE
* Glassfish 3.2
* MySQL 5.2
* JPA
* Eclipse
* Git

Overall it did go well, but there were certain life lessons that I doubt I will ever forget!

#### If there no financial gain, it's hard to motivate

... Well its not limited to just monetary gain, it's just about the **want** to do the job that you've been given, such as the Open Source community. People want to contribute and make a better piece of software, whereas most students are just happy with a degree, let alone a first class honours. 

#### Paperwork, Paperwork and more Paperwork...

I know this may seem a little childish, but I dislike paperwork, not because it's hard or even tedious, it's mainly because of the ease that it can be damaged, and how hard it is for people to know what exactly is being done. For example we should have used Change of Control Forms (CCF) for making changes to documents and such. However, why would you use CCFs when you have a fully integrated issue tracker in Github? We were then able to create and allocate issues to people, giving the maintainer the ability to comment if there is a problem -- which is all logged to be reviewed at a later date!

#### Commercial tools are hacky

This is more of a rant about [Java Persistence API][1] more than anything. When I came to research about JPA, it seemed like a great idea! Objects which describe exactly what the database has -- *b-e-autiful*. However, since most database management solutions are updated more often than Oracle releases a patch, new features I want to use are not supported. My main quip with it is lack of a boolean type in JPA, it is normally simpler to use a TINYINT(1) or  a char.

[1]: http://www.oracle.com/technetwork/java/javaee/tech/persistence-jsp-140049.html 

In the end, I did bring a lot of good lessons out of this task; but there is one more important lessons out of all -- DON'T TRUST ANYONE!
