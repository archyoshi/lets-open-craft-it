@snap[midpoint span-90]
## @color[orange](H)ow to @color[orange](C)ontribute to @color[orange](O)pen @color[orange](S)ource
@snapend
### Special Edition

---

@snap[north span-100]
### What's on the menu ?...
@snapend

@snap[midpoint toc]
@ul[](false)
* Open Source you say ?
* A simple recipe...
* Some technical gestures to get you going...
* Let's give it a try
* Your turn now !
@ulend
@snapend
---

@snap[north span-100]
### Open Source you say ?
@snapend

@snap[west span-15]
![osi_logo](https://opensource.org/files/osi_standard_logo_0.png)
@snapend

@snap[east span-80 text-left]
The term "open source" refers to something people @css[underline](**can modify**) and @css[underline](**share**) because its design is @css[underline](**publicly accessible**).
<br><br>
Open source doesn't only mean "free", but it's also has lot more advantages like:
*Control, Secutiry, Stability etc...*
@snapend

@snap[south template-note text-gray span-100]
@size[0.5em](Find more info here at https://opensource.com/resources)
@snapend
---

@snap[north span-100]
### A simple recipe...
@snapend

@snap[midpoint toc span-100]
@ul
* Choose a project that inspires you
* Check whether this project is "really active"
* Go to visit :)
* pick up an issue where you want to start
* read contribution guidelines
* clone project, do the magic then send the pull request
@ulend
@snapend

---
@snap[north span-100]
### Some technical gestures to get you going...
@snapend

@ul[](false)
* you need a fork, not a knife ;)
* clone it to your computer
* make a wonderful commit
@ulend

+++
@snap[north span-100]
### Forking !
@snapend

@snap[span-100]
![forking](https://www.dataschool.io/content/images/2014/Mar/github1.png)
@snapend

@snap[south template-note text-gray span-100]
@size[0.5em](image from https://www.dataschool.io/simple-guide-to-forks-in-github-and-git/)
@snapend

+++
@snap[north span-100]
### Syncing your project before you start working
@snapend

```shell
$ git remote add upstream  https://github.com/joel-costigliola/assertj-core.git
$ git fetch upstream
$ git checkout master
$ git merge upstream/master
```
@ul[](false)
* More info here : [syncing a fork](https://help.github.com/en/articles/syncing-a-fork)
* and some more here : [setup remote](https://www.neonscience.org/git-setup-remote)
@ulend
+++
@snap[north span-100]
### Syncing !
@snapend

@snap[span-100]
![syncing](https://www.dataschool.io/content/images/2014/Mar/github2.png)
@snapend

@snap[south template-note text-gray span-100]
@size[0.5em](image from https://www.dataschool.io/simple-guide-to-forks-in-github-and-git/)
@snapend
---

@snap[north span-100]
### Let's give it a try
@snapend

@snap[west span-100]
[AssertJ](https://github.com/joel-costigliola/assertj-core), developped by Joel Costigliola
<br><br>
[AssertJ](https://github.com/joel-costigliola/assertj-core) is a @css[underline](*java library*) providing a rich set of @css[underline](*assertions*), truly helpful error messages, improves @css[underline](*test code readability*) and is designed to be super easy to use within your favorite IDE.
@snap[north span-100]

+++

@snap[north span-100]
### Contribution guidelines
@snapend

@snap[west span-100]
[Guidelines](https://github.com/joel-costigliola/assertj-core/blob/master/CONTRIBUTING.md)
, *example :*
<br><br>
@ul
* naming conventions for variables, test classes
* where to contribute, merge, fork ?
* general guidelines for code style
* javadoc style (if it's java of course ;) )
* legal stuff
@ulend
@snapend

---
@snap[north span-100]
## Now it's your turn !
@snapend

@snap[midpoint span-100]
Don't forget, even correcting a spelling mistake in a documentation is considered as a contribution :)
so don't be shy nor afraid, and go ahead, do your first contribution !
@snapend

---

@snap[north span-100]
### Thanks for coming
@snapend

@snap[midpoint span-80]
@ul[](false)
- Come to my Meetup next September [Let's open Craft it](https://www.meetup.com/fr-FR/Paris-Lets-Open-Craft-It-contribute-to-open-source/)
- Follow me on twitter [@archyoshi](http://twitter.com/archYoshi)
- Find me on linkedin [inaflasthami](https://www.linkedin.com/in/inaflasthami/)
- Find my slides at [https://gitpitch.com/archyoshi/lets-open-craft-it](https://gitpitch.com/archyoshi/lets-open-craft-it)
@ulend
@snapend
