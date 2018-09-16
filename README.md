# Flask Exercise: making guestbook app
A guestbook app.

1. View: templates for adding an entry and displaying the guestbook
<br> - index.html (in /templates): template for showing the guest book
<br> - addentry.html (in /templates): template for allowing a visitor add a message
<br> - style.css (in /static): a style sheet to make it look amazing

2. Model: handling updates, maintaining the list of entries
<br> - model.py: contains init function and access function (to get the list of current entries)
  
3. Controller: setting up routes and mapping data to views
<br> - app.py: / route — display guest book; /add route — display message entry form; /postentry route — receive post data from the /add route 


Reference:
  SI507 Lecture Note (Lecture 25) 
