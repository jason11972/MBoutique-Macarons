# MBoutique

## Scope

### templating ###

- template repeating parts
  - header
  - footer

### dynamic menu generation ###

- create an associative array
  - with all of the menu items from the header (about, contact, home, etc)
  - make nested key value pairs
  - array should contain the following information for each link
    - the menu item name
    - the URL to go to in the a href
    - whether the menu item is the default menu item (the item to display on initial page load)
- create the menu dynamically, from the associative array, in php

### display the home page based on the default page in the 
- using include, display the home page based on the dynamic array defined above
