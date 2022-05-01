
Hello! My name is Patricia, this is my Repository

# introductoryProgramAltimetrik
Card Number #48

Git branching strategies and flows.
Git flow is the set of guidelines that developers can follow when using Git.
It is referred to as Branching Model by the developers and works as a central repository for a project. Developers work and push their work to different branches of the main repository.
-There are different types of branches in a project. 
Master Branch : The master branch is the main branch of the project that contains all the history of final changes.

Develop Branch: It is parallel to the master branch. It is also considered as the main branch of the project. This branch contains the latest delivered development changes for the next release

Hotfixes Branch: The hotfix branches arise due to immediate action on the project. In case of a critical bug in a production version, a hotfix branch may branch off in your project. After fixing the bug, this branch can be merged with the master branch with a tag.

Release branches: The release branch is created for the support of a new version release

Feature branches:  It is used to develop a new feature for the next version of the project. The existence of this branch is limited; it is deleted after its feature has been merged with develop branch.

bibliography:

https://www.javatpoint.com/git-flow
https://css-tricks.com/branching-strategies-in-git/

Handbook : ( https://docs.google.com/document/d/1x8fwaIwzl5pjtvPh0w6tgf2TVn30Df1oABnpORPgLhQ/edit# )


Data attribute ( https://docs.google.com/document/d/1x8fwaIwzl5pjtvPh0w6tgf2TVn30Df1oABnpORPgLhQ/edit# )

The data-* attribute is used to store custom data private to the page or application.
consist of two parts:
The attribute name should not contain any uppercase letters, and must be at least one character long after the prefix "data-"
The attribute value can be any string
Is a Global Attribute, and can be used on any HTML element.
(The global attributes are attributes that can be used with all HTML elements.)

syntax
Any attribute on any element whose attribute name starts with data- is a data attribute

<article
  id="electric-cars"
  data-columns="3"
  data-index-number="12314"
  data-parent="cars">
...
</article>

