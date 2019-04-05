# mini-cms
Finding the minimalistic code-base for a working CMS (ongoing project)

After seeing many implementations of Rails projects, which were highly over-engineered, historicly grown and in dire need of refactorings, I wanted to try to find a professional and clean way: Using as few dependecies and following ruby and rails conventions as much as possible, which will create a easy maintainable and expandable code-base.

I plan on various branches, which will showcase features, so you can checkout desired funtionalities and merge them (hopefully without conflicts)

1. Master branch

Using a MySQL Database and a pure Rails Frontend/Backend without styles and js-Frameworks (except those which already are included in RailsCore, e.g. jQuery). A Junior Rails Dev should be able to maintain this with ease.

2. Bootstrap Responsiveness

Using the latest Bootstrap version to showcase grid functionality and other useful features and styles

3. Simplifying a devs work

HAML and SASS as code precompilers, which save a lot of (redundant) code. SimpleForms gem (which works nicely with Bootstrap) produces forms with less code than base. This branches' output will look the same to the user, but its a foundation to save code and makes working on it easier when you get used to it.

4. React Frontend

Showcasing one-page app with Rails APIs

5. More features to come, that I want to have while coding previous steps
