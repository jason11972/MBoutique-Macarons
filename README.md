# MBoutique

## Scope

### templating ###

- template repeating parts
  - header
  - footer

### dynamic menu generation ###

- Create your top menu dynamically via data in an associative array
- links in the menu should all make requests to index.php
- each link should pass data to index.php via the query string

### in index.php:
- show the center content plus any related content (some of you have custom CSS files) based on the passed in query string data
- verify that the query string is set.  if not, go to a default value
- if the query string variable points to an invalid entry, go to 404.php that has a 404 message

### for contact.php
- make the form go to index.php, page contact, via the query string
- form should use the post method
- if post data for the form is supplied, it should show the data supplied, NOT the form.


