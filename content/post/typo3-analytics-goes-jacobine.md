+++
categories = ["Jacobine", "Open Source"]
date = "2014-04-22T12:45:13+02:00"
draft = false
featureimage = ""
menu = ""
tags = ["analytics", "development", "Jacobine", "metrics", "open source", "software repository mining", "typo3"]
title = "TYPO3-Analytics goes Jacobine"
+++

For quite some time i was looking for a new name for an open source project of mine: *TYPO3-Analytics*.

I am (sadly) not creative in naming things or painting.
The biggest part of creativity is during development and programming.
To find a good name which sounds nice and got a relation to a tool, task or goal is (in my point of view) very difficult.

<!--more-->

There are some names of projects i like, because the sound good like [Flynn.io](https://flynn.io/) or [hood.ie](http://hood.ie/).
At 3rd March 2014 i wrote a blogpost about this challenge to use the power of the community: TYPO3-Analytics is looking for a new name - suggestions welcome!

Next to this blog post i got on my girlfriends nerves with the recurring questions like "What do you think about name x? Or y?".
And i asked my twitter timeline many times and wondered how for example Apache chose names for their product.
They [got rules for product names](http://www.apache.org/dev/project-names.html), but i did not found a resource who describes the story about this names.
[Ingo](https://twitter.com/irnnr) [mentioned](https://twitter.com/irnnr/status/449367546211221504) that [Tika](https://tika.apache.org/) is one of the project founders’ kid’s toy pet’s name.
[Scott](https://twitter.com/shirleman) [suggested](https://twitter.com/shirleman/status/449614357022773248) Donk, because it was his stuffed donkey's name as a kid :D
Anyway.

I thought a lot about possible names and talked to many people.
Some of the ideas were *Vizben*, *Benvis*, *Mevis*, *Pinocchio*, *Gepetto*, *Viva con analysis*, *Knock.io* and so on.
Nothing special.
Nothing "good" enough.
Nothing i like at the first time.
So i continued my search.
During a lunch break i talked to my colleagues [Jan](https://twitter.com/janvanthoor) and [Dominik](https://twitter.com/milchjieper) about this topic.
Jan mentioned that i might have to chose a general topic which i focus on for the name search.
He suggested mining.
I liked the idea and started my research in the mining area ...

## The new name: *Jacobine*

I was born and live in [Duisburg, Germany](http://en.wikipedia.org/wiki/Duisburg).
Duisburg is a small town in [North Rhine-Westphalia](http://en.wikipedia.org/wiki/North_Rhine-Westphalia) and part of the Ruhrgebiet.
Duisburg is very popular for its steel industry and coal mining (see the [Landschaftspark Duisburg-Nord](http://en.wikipedia.org/wiki/Landschaftspark_Duisburg-Nord) or a [list of coal mines in Duisburg](http://de.wikipedia.org/wiki/Liste_von_Bergwerken_in_Nordrhein-Westfalen#Duisburg)).
In 1855 an english company started to build a new mine called *Jacobine*.
It was located in Duisburg-Meiderich near to [Oberhausen](http://en.wikipedia.org/wiki/Oberhausen).
In 1859 the mine have to shutdown, because it was damaged by water.
11 years later, in 1870, the mine was repaired.
In 1871 the mine was put into production again under a new name Schacht 1.
Schacht 1 was part of the bigger mine [Westende](http://de.wikipedia.org/wiki/Zeche_Westende).

Dominik mentioned that the name *Jacobine* got a bad taste, because it was damaged and has to be shutdown.
Dominik is right, but the mine was repaired and put into production again.
I would agree Dominik that *Jacobine* is a bad name for a management software or something in this area.
But we do not build a management software ;)
And one important fact: I like the new name.
It is unique in the software world (as far as i know), it got a relation to the main area of the tool we build ([data]mining) and a relationship to my lovely town Duisburg (but of course contributor from other cities and countries are welcome as well :)).

**So lets try to get not damaged by water :)**

## Migrate your TYPO3-Analytics clone

If you got an existing clone of the project with the old name TYPO3-Analytics you have to migrate the git repository to keep up to date.
Here we go:

```bash
$ git remote -v
origin git@github.com:andygrunwald/TYPO3-Analytics.git (fetch)
origin git@github.com:andygrunwald/TYPO3-Analytics.git (push)

$ git remote set-url origin git@github.com:andygrunwald/Jacobine.git

$ git remote -v
origin git@github.com:andygrunwald/Jacobine.git (fetch)
origin git@github.com:andygrunwald/Jacobine.git (push)
```

Please pay attention to the name of your remote (origin or maybe [upstream](https://help.github.com/articles/syncing-a-fork)) and the protocol you use (*git://* or *https://*).

The ecosystem around *Jacobine* (the [web frontend](https://github.com/andygrunwald/TYPO3-Analytics-Web), the [vagrant machine](https://github.com/andygrunwald/TYPO3-Analytics-Vagrant) and the [chef cookbook](https://github.com/andygrunwald/chef-typo3analytics)) will be renamed in the next days.

If you got any kind of problems or need help to migrate your clone i will help you as much as possible.
Just add a comment, send a tweet ([@andygrunwald](https://twitter.com/andygrunwald)) or send me an email.

PS: Thanks to all people who was involved to find a new name and attend all the discussions!
PPS: And thanks to [Georg](https://twitter.com/georg_ringer), [Lena](https://twitter.com/ffffux), [Ben](https://twitter.com/benvantende) and [Ola](https://twitter.com/misprintedtype) who attend my [last survey on twitter](https://twitter.com/andygrunwald/status/458286697416245249) regarding *Jacobine* or *Jacob* (self made abbreviation for *Jacobine*) - 3:1 for *Jacobine*!