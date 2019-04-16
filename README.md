# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
I basically changed the whole design and layout of the blog by creating a Todo List. I used a style that I saw was commonly used throughout Todo Lists and went from there far as the background color as well transparency

I created a class where I  can List the Todos that I created and have the option of checking and crossing out the Todo as well having a delete option which I implemented in the todo_lists_controller.rb. I made sure to implement a if /else statement inside of the _todo_item.html.erb to help with the delete button. I struggled with frustrated this and got very frustrasted with the whole concept of coding and using the terminal. Some things I didnt know I was suppose to do such as typing rails server into the terminal to activate the localhost. Then when using the terminal for the other things Im suppose to turn it off by using Crtl + C. The internet helped alot when I couldn't figure out what to do as well my classmates. I followed a structure and I got stuck with most of the code so somethings might not be perfect within my code meaning certain buttons or options might not work as they should but I tried my best. 

I worked mainly in these files.
1. routes.rb
2. todo_list.rb
3. todo_items_controller.rb 
4. _todo_item.html.erb and _form.html.erb (Partial)
5. show.html.erb
6. “missing partial todo_items/_form” ( This kept popping up and this where I got stuck at).
7. application.scss ( The structure of the site Box Table.
8. I had to create some files that weren't available. Ex.(_todo_item.html.erb and _form.html.erb).  
9. edit.html.erb
 Scaffolds I used: rails g model todo_item content:string todo_list:references, rails g scaffold todo_list title:string description:text.





