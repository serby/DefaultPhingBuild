Maid the Clock Setup, Build and Deploying Tool
============

Developers
----------
* Paul Serby <paul.serby@clock.co.uk>
* Dom Udall <dom@synthmedia.co.uk>
* Elliot Coad <elliot.coad@clock.co.uk>

Introduction
------------

Maid is a build and deployment mechanism constructed using Phing. It's purpose ranges from setting up 
projects within virtual machines, cleaning up files, codesniffs, and deployment, aiming to reduce project-specific
 knowledge and chance of human error.

Installation
------------

* Copy the build files into your project.
* Update build.properties as necessary.
* Customise/hack away!

Merge Strategy
--------------
All new development should be merged back to branches/Develop/trunk before merging down to trunk for the live deployment. 
