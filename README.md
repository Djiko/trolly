# [Trolly](http://github.com/djiko/trolly)

Trolly is a shopping list application for android, aiming at being very simple : no annoying, complicated or unnecessary features. 
Trolly has initially been released by [Ben Caldwell](https://code.google.com/p/trolly/) as a [GPL V3](http://www.gnu.org/licenses/gpl.html) open source project.

## Features

Trolly lets you create shooping lists, keeps track of added product and helps you manage your shopping time by giving you a quick and easy access to the list. 

## Licence

Trolly is a free software released under the GPL V3 licence. 

### Bugs
  + **Locale issue** : some warning are showing in the code, due to Locale, specifically in the Trolly class.
  + **Openintents issue** : as is, the project will not compile because an **openintents** issue.
  + **\' issue** : this problem might be existing in other languages. In French, if you use an apostrophe in a product's name, the application will crash. 

### TODO: Improvements
  * UI -> implement a side menu
  * Add French translation. COntributions are welcome if you are willing to add your own language
  * Cleaning the cached product list is not that intuitive. There may be some improvements to do there. 
  * follow up prices and shops : why not logging shops and prices ? Maybe compare shops for the same list
  * Create list from reference list : build a reference list and create new list from it
  * Posting and getting lists over http to share your lists
  * Getting product image over http

## Bug Tracker / Features requests

Have a bug or a feature request? [Please open a new issue](https://code.google.com/p/trolly/issues). 
Before opening any issue, please search for existing issues.
Before requesting a new feature, keep in mind that Trolly is meant to be simple. If your feature seems complicated, it might be a good time to make it more simple.
