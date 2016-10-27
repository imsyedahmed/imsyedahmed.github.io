---
layout: post
title:  "export & import database using mysql command line"
image: ''
date:   2016-10-27
tags:
- mysql
description: ''
categories:
- database
serie: learn
---

## Why Command Line ?

Using command line is very good thing for a developer or a software engineer. Without knowledge of command line linux / unix platform user can't take full advantage (or can't accelerate development work) of their platform. Its very powerful for unix / linux user. Here i will not describe full details of using command line ;) may be later or not :P

Sometimes export & import database using phpmyadmin tools create some problem specially when database size is too big!

So for that reason you can do it using command line.

## Import Command

Using belows command you can import database --
{% highlight shell %}
mysql -u USERNAME -p database_name < database.sql
{% endhighlight %}
after this command you need to input your mysql user password.

## Export Command
Using belows command you can export database --
{% highlight shell %}
mysqldump -u USERNAME -p database_name > database.sql
{% endhighlight %}
here also you need to input your mysql user password.

Thanks :)
