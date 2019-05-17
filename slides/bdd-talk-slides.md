autoscale: true
build-lists: true
theme: Top20Talent
footer: © TOP20TALENT, 2018. Proprietary and confidential.

![inline](https://www.froglogic.com/wp-content/uploads/2016/05/BDD.png)

# **Behavior-Driven Development with Python**

-

## **by** Evgeny Demchenko

[.background-color: #000000]
[.header: #FFFFFF]
[.header-strong: #FFFFFF]

---

## [fit] **TALK** _OUTLINE_

* What is **BDD**?
* **Gherkin** language
* Python tools for **BDD**
* Examples

---

# [fit] WHAT IS _BDD_?

![inline](https://vikramviknowledgesharing.files.wordpress.com/2017/01/bdd-workflow-600x268.png?w=600)

---

# [fit] THE MANY NAMES OF _BDD_?

* "Outside in TDD"
* "Acceptance Test-Driven Development" (ATDD) 
* "Specification by Example"

---

# [fit] **BENEFITS** OF _BDD_

* Focuses on business outcomes rather than implementation details
* Tests the whole feature
* Created a common language between business and development 
* Promotes collaboration and shared artifacts
* Allows "executable specs"

---

# [fit] _GHERKIN_ LANGUAGE

![inline](https://pacroy.github.io/uploads/tdd/given-when-then.jpg)

---

# [fit] **GIVEN**-_WHEN_-THEN

Is a template for writing of acceptance criteria:

* __(Given)__ some context
* __(When)__ some action is carried out
* __(Then)__ a particular set of observable consequences should obtain

---

# [fit] **GHERKIN** SCENARIO _EXAMPLE_

```gherkin
Feature: Blog
    A site where you can publish your articles.
    
Scenario: Publishing an article
    Given an author user 
        And they have 2 articles  
    When they publish a new article
        And visit the articles page
    Then there are 3 articles in the list
        And the new article is on top
```

---

# [fit] _PYTHON_ TOOLS

* [pytest-bdd](https://github.com/pytest-dev/pytest-bdd)
* [Behave](https://github.com/behave/behave)
* [Robot framework](https://robotframework.org/)
* [radish](http://radish-bdd.io/)
* [lettuce](http://lettuce.it/)

![right 700%](https://docs.pytest.org/en/latest/_static/pytest1.png)

---

# [fit] _EXAMPLES_

---

![inline 90%](https://www.top20talent.com/wp-content/uploads/2017/09/logotype-1.png)

# Thanks!
