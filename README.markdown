Disclaimer
==========

I am NOT a modern javascript developer. I am hacking this apart to serve my own purposes and just have it not crash. Expect errors and/or inelegant but expedient coding choices. Any help/improvements are welcome.

This branch contains the option to turn off point badges on cards. Next I will hopefully change the update interval.

Scrum for Trello
===========

Scrum for Trello adds functionality to the awesome trello.com for use in Scrum projects.

Trello is the perfect online equivalent of the whiteboard with sticky notes aka the Scrum
board. One element we use are the storypoints. TrelloScrum gives you the ability to
make use of story points in Trello.

Setup
-----

The orignal Scrum for Trello is a Chrome extension and you can install it via the Chrome Webstore, and was the wonderful source of this fork. 

To install this fork/version, clone this repository and load the TrelloScrum folder as an unpacked extension.
(Under chrome://extensions/ turn on developer mode, then click load unpacked extension and point to the cloned directory.)

Also, don't blindly trust people on the internet - look at the [diff between this fork and the original](https://github.com/Q42/TrelloScrum/compare/master...julowe:minimal) yourself and verify the changes.

How does it work?
-----------------
In the card titles you can add the storypoints between parentheses. The assigned points
will be picked up by TrelloScrum and displayed in the upper right corner of the card.

For each list the total amount of story points will be calculated and shown in the title
of the list.

Every second the story points will be detected and calculated. So changing a number or moving
a card will be reflected almost immediately.

Why did I fork this?
--------------------
Trello was slow. It was painful to move cards around, and sometimes even scrolling was unmanageable. And as I just recently figured out, this extension stops other powerups from working - google drive and bitbucket in my experience.

Credits
-------
TrelloScrum was developed by [Marcel Duin](http://webglmarcel.q42.net/) and [Jasper Kaizer](https://twitter.com/jkaizer)
during our pet projects time at [Q42](http://q42.com).

Great improvements made by @nicpottier and @paullofte:

* The point value is moved to be a badge on the card.
* Added support for Zero Point Cards (0), Unknown Point Cards (?), Decimal Value Cards (.5)
* In addition I added the functionality to have the list total reflect the current filtered set of cards.

