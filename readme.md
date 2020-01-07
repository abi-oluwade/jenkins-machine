# JENKINS

This jenkins readme is located only on the 'home' branch, we learnt how to switch between
the dev and master branch and had jenkins listen to only the dev branch and build when changes have
been committed to that branch.

## What is it and what is it for?

Jenkins is an open-source continuous integration software tool written in the Java programming language for testing and reporting on isolated changes in a larger code base in real time. The software enables developers to find and solve defects in a code base rapidly and to automate testing of their builds.

Say you develop a software. You might have unit tests bundled in your software. A Jenkins job could watch your software's git repository and run these tests for you, like you would do manually, whenever a new commit is pushed.

If the tests are successful, you might want Jenkins to package/bundle/compile your software to produce an artifact you can install or deploy.

When you have that artefact ready, you might even want Jenkins to deploy it for you in production.

It has the tools and plugins to help you do that but really you can do what you want using, for example, the shell provisioner to run bash/python/ruby/whatever scripts and commands.
