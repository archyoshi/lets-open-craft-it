# @color[orange](L)et's @color[orange](O)pen @color[orange](C)raft @color[orange](I)t
### Edition 0

---

@snap[north span-100]
### What's on the menu ?...
@snapend

@snap[midpoint toc]
@ul[](false)
* It starts...
  * A bit about me ...
  * Define : Let's open craft it
  * The project : AssertJ
  * Finally some code !!
* Let's read some stuff
  * The issue
  * Contribution guidelines
* Let's start crafting
  * Clone & Craft
  * Contribute !
* Retro / Feedback
@ulend
@snapend
---
# It starts...

+++?image=template/img/bg/white.jpg&position=left&size=10% 100%

@snap[north span-100]
### A bit about me ...
@snapend

@snap[west span-30]
![](assets/img/profile_me.jpg)
@snapend

@snap[east span-70 text-white]
@ul
  * Engineer, software craftsman (and proud to be)
  * Java++ / search engines
  * love games, music and life
@ulend
@snapend

+++

@snap[north span-100]
### Define : Let's open craft it
@snapend

@snap[west span-15]
![osi_logo](https://opensource.org/files/osi_standard_logo_0.png)
@snapend

@snap[east span-80]
@color[orange](**Learn**) together and @color[orange](**contribute**) to @color[orange](**open-source**) projects
<br><br>
@color[orange](**Apprendre**) ensemble et @color[orange](**contribuer**) à des projets @color[orange](**open-source**)
@snapend

+++

@snap[north span-100]
### The project : AssertJ
@snapend

@snap[west span-100]
[AssertJ](https://github.com/joel-costigliola/assertj-core), developped by Joel Costigliola
<br><br>
[AssertJ](https://github.com/joel-costigliola/assertj-core) is a @css[underline](*java library*) providing a rich set of @css[underline](*assertions*), truly helpful error messages, improves @css[underline](*test code readability*) and is designed to be super easy to use within your favorite IDE.
@snap[north span-100]

+++
@snap[north span-100]
### Finally some code !!
@snapend

```java
import static org.assertj.core.api.Assertions.assertThat;
import org.junit.jupiter.api.Test;
public class SimpleAssertionsExample {
  @Test
  void a_few_simple_assertions() {
    assertThat("The Lord of the Rings").isNotNull()   
                                       .startsWith("The")
                                       .contains("Lord")
                                       .endsWith("Rings");
  }
}
```

@snap[south-west template-note text-gray]
@size[0.5em](Example taken from https://assertj.github.io/doc/#assertj-core-assertions-guide)
@snapend

---

# Let's read some stuff

+++

@snap[north span-100]
### The issue
@snapend

@snap[west]
[Display group of values in ShouldHaveSameSizeAs](https://github.com/joel-costigliola/assertj-core/issues/1522)
<br><br>
When *hasSameSizeAs* fails, it only displays the size of the iterable/array/map. It might certainly be useful to show both iterable/array/map to ease understanding why the sizes differ.
@snapend

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

---
@snap[north span-100]
### Thanks to all participants for being here :
@snapend

@snap[midpoint toc]
@ul[](false)
* Zineb
* Mahdiou
* Arnaud
* Arnaud 2
* Ibtissam
* Fabrice
@ulend
@snapend

---

@snap[midpoint span-80]
@ul[](false)
- Follow me on twitter [@archyoshi](http://twitter.com/archYoshi)
- Find me on linkedin [inaflasthami](https://www.linkedin.com/in/inaflasthami/)
- Find my slides at [https://gitpitch.com/archyoshi/lets-open-craft-it-1](https://gitpitch.com/archyoshi/lets-open-craft-it-1)
@ulend
@snapend
