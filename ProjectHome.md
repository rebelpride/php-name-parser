The goal of this project is to develop an intelligent algorithm for splitting full names into the following parts:

  * Salutation
  * First Name
  * Initials
  * Last Name
  * Suffix

This project also attempts to fix some common formatting issues like capitalization.

Initial information about this project can be found at:
http://www.onlineaspect.com/2009/08/17/splitting-names

The main things on the to-do list are:
  * refactor as a PHP class
  * separate splitting from formatting
  * remove any words in parenthesis (not just 1 word)
  * handle the "Lname, Fname" format
  * pull out the various dictionaries and make them easier to modify
  * add rule to capitalize two letter names w/ no vowels (ex. "JP" but not "Jo")
  * add common name libraries to allow for things like gender detection