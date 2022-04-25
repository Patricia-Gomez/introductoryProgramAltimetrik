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

