Recipes
=======

a ruby on rails 5.0 example app
to learn about the asset pipeline.

clone this repository, then

    bundle
    rails db:migrate
    rails server

now point your browser at the homepage at http://localhost:3000/
or at http://localhost:3000/todo.html 

You will be asked to

* load seed data
* explore the unobstrusive javascript created by the rails scaffold
* configure the app to use EcmaScript 6 (ES6)
* write your own nobstrusive javascript that calls a ES6 class
* switch on Turbolinks
* Use AJAX to create and "inline editing form"


1)Load seed data
	What is seed data? 
		seed data sind datensätze für die Datenbank
	Where is the actual file located? 
		Im Ordner db in der App befindet sich die Datei seeds.rb
	And what was that rake task to load it?
		rake db:seed

2)Understand Unobstrusive JavaScript
	Look at the HTML-Code for deleting and ingredient: where does the JavaScript to confirm come from?

	Try applying the same to a normal navigation link - does it also show the confirmation-popup?
	Ja es zeigt auch den Alert

	Compare the code in the JavaScript Playground with what you learned about unobstrusive JavaScript in backend-development.github.io. You will be needing it soon!

3)Use Plain JavaScript
	Write JavaScript code that adds the current time to every page.

	There's nothing Rails specific about this, just a few lines of jQuery, a new Date and setInterval should suffice.
