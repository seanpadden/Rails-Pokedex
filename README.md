# Pokédex

Hello there! Welcome to the world of Pokémon!

<img src="https://cdn.bulbagarden.net/upload/8/84/Professor_Oak_XY.png" width="160" height="290">

My name is Oak! People call me the Pokémon Prof!  
This world is inhabited by creatures called Pokémon!  

All `Pokémons` have a string `name`, integer `weight` and a string `description`.

How would you like to help me out? I am currently working on the latest version of the Pokédex, built out in Rails. It lets us catalogue any Pokémon you've seen.

With this Pokédex, I want to be able to:

* See the names of all the Pokémons on an index page. Each of the names on the index page should link to the respective Pokémon's show page. (See the next deliverable)

* See a specific Pokémon's information regarding its name, weight and description on a show page.

* Log any new Pokémon via a form. After the Pokémon is created, I should be taken to the newly created Pokémon's show page.

* Edit a Pokémon's weight and description. After the Pokémon is created, I should not be able to edit its name, but only its weight and description. Make sure that this is accounted for when building out your edit form and strong parameters. After the Pokémon is edited, I should be taken to the proper show page.

* Validate that every Pokémon in the database has a name and a weight.

* Validate that every Pokémon in the database has an integer weight that is greater than zero.

* Validate that every Pokémon in the database has a description that is 50 or fewer characters.

Be sure to follow RESTful routing when building this Rails Pokédex! You'll need to create your own migrations, model and database, so you've your work cut out for you!

If you are done, perhaps you can figure out a way to incorporate images into the Pokédex, using external URL's!
