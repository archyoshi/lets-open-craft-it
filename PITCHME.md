# @color[orange](L)et's @color[orange](O)pen @color[orange](C)raft @color[orange](I)t
### Edition 1

---

@snap[north span-100]
### What's on the menu ?...
@snapend

@snap[midpoint toc]
@ul[](false)
* It starts...
  * a brief reminder
  * one last thing...
* Let's start crafting
  * Clone & Craft & Contribute
  * the issue (from last time)
  * a new issue to investigate
* Retro / Feedback
@ulend
@snapend
---
# It starts...

+++
@snap[north span-100]
### A brief reminder ...
@snapend

@snap[midpoint toc span-80]
@ul[](false)
  * intro to open source contributing process
  * some notes and discussions
  * live demo
  * a first pick into [AssertJ](https://github.com/joel-costigliola/assertj-core)
  * first thoughts about solving issue : [Display group of values in ShouldHaveSameSizeAs](https://github.com/joel-costigliola/assertj-core/issues/1522)
  * contribution on assertJ [Guidelines](https://github.com/joel-costigliola/assertj-core/blob/master/CONTRIBUTING.md)
@ulend
@snapend

+++
@snap[north span-100]
### one last thing ...
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

---

# Let's start crafting

+++
@snap[north span-100]
### Clone & Craft & Contribute
@snapend

@snap[north span-30]
<br><br>
<br><br>
@box[bg-orange text-white box-wide-padding rounded](#__Clone__)
@snapend

@snap[south-east span-30]
@box[bg-green text-white box-wide-padding rounded](#__Craft__)
@snapend

@snap[south-west span-30]
@box[bg-blue text-white box-wide-padding rounded](#__Contribute__)
@snapend

@snap[midpoint]
<br><br>
<br><br>
@fa[refresh fa-3x]
@snapend

+++
@snap[north span-100]
### the issue (from last time)
@snapend

@snap[west span-100 text-justify]
[Display group of values in ShouldHaveSameSizeAs](https://github.com/joel-costigliola/assertj-core/issues/1522)
<br /><br />
When *hasSameSizeAs* fails, it only displays the size of the iterable/array/map. It might certainly be useful to show both iterable/array/map to ease understanding why the sizes differ.
@snapend

+++
@snap[north span-100]
### a new issue to investigate
@snapend

@snap[west span-100 text-justify]
[Provide comparable assertions for non comparable class when given a comparator](https://github.com/joel-costigliola/assertj-core/issues/1492)
<br /><br />

*Comparable assertions* are restricted to Comparable types, this could extended for non Comparable types if a proper Comparator is given.
@snapend

+++
@snap[north span-100]
### a new issue to investigate
@snapend

```java
  Foo foo1 = ...;
  Foo foo2 = ...;
  FooComparator fooComparator = ...;
  assertThat(foo1).usingComparator(fooComparator).isGreaterThan(foo2);
```
---
@snap[north span-100]
### Thanks to all participants for being here :
@snapend

@snap[midpoint toc]
@ul[](false)
*
@ulend
@snapend

---

@snap[midpoint span-80]
@ul[](false)
- Follow me on twitter [@archyoshi](http://twitter.com/archYoshi)
- Find me on linkedin [inaflasthami](https://www.linkedin.com/in/inaflasthami/)
- Find my slides at [https://gitpitch.com/archyoshi/lets-open-craft-it](https://gitpitch.com/archyoshi/lets-open-craft-it)
@ulend
@snapend
