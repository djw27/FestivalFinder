FestivalFinder
==============

Festival Finder App for the UK festival scene.

Dependencies:
Django 1.7
MySQL-python

This code is in no way production ready. The app attempts to utilise simple natural
language processing to extract search terms and return to the user a list of relevant festivals. For example:

"A small rock festival next summer"

should return all festivals which are "small", contain "rock" music and occur in a predetermined timeframe for "summer".

There currently exist some bugs which will be fixed given time. A live version of this repository can be found here: http://sheligalo.alwaysdata.net/
