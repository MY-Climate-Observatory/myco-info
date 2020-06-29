# MYCO Contributing Guidelines

As most MYCO contributors come from various backgrounds, there are many ways that they can make meaningful contributions:

* Research and propose a climate metric that MYCO could host
* Create pull requests of changes for typos or even major flaws
* Report bugs or issues
* and more!

## Coding Styles

If you are editing an existing code, please do your best to match the existing formatting so that it is easier to read. Consistency of layout will go a long way!

One golden rule of formatting -- please don't use tabs in your code as they will cause the file to be formatted differently for different people depending on how they have their editor configured.

## Comments

Either you are making a small edit or contributing a whole script, please add in commments for your code describing what it does, and also *why* it works. 
This will be helpful to help our community members to better understand your code.

A general guideline:

* include docstrings for all modules, functions, class or methods
* include comments for code that might be difficult to understand what the code does, and why it should be the way it is
* make sure your comments are not misleading
* don't go overboard, a one-paragraph comment would not be helpful for a one-liner code

## Committing 

When you submit patches, the project maintainer has to understand them to patch them onto the master branch. 
This is very difficult, and misunderstanding patches can lead to them being more difficult to merge. 
To help prevent misunderstanding, when submitting you should:

* Split up large patches into smaller units of functionality.
* Keep your commit messages relevant to the changes in each individual unit.

When writing commit messages please try follow this style, namely:

* A one line summary, starting with a capital and with no full stop.
* A blank line.
* Full description, as proper sentences with capitals and full stops.

For simple commits the one line summary is often enough and the body of the commit message can be left out.

If you have forked on GitHub then the best way to submit your patches is to push your changes back to GitHub and then send a "pull request" on GitHub.
