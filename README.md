# Simplest Swipe Cards  *By [Michael Sitver](http://www.Michaelsitver.com)*

# Introduction:
These are the simplest, most beautiful Tinder swipe cards on the web. They don't require Node.JS, or React, or hosting a new stylesheet, or anything of the sort. **You can literally copy/paste them onto your existing static website**.

They're also extremely lightweight.
**Demo the cards [here](http://pleasant-flag.surge.sh)**
# Stack:
They're written in:
- HTML
- JS (with a smattering of Jquery)
- And CSS
That's it!

There are a few small dependencies, but they're all hosted for free on solid CDNs, and well-supported on StackOverflow:
- JQuery, JqueryUI, and JQuery Mobile (the magic that makes these work)
- FontAwesome - optional, but included (for the two icons)
- Animated library (for those beautiful swipes and fades)
# More advanced Stuff (See Washingtinder.html)
"But Michael, what about voting?" "What about multiple cards?" "What about menus and notifications?"

I hear you!

I've included an example of SimplestSwipeCards in action, with all these features! The best part is that it only adds a hair of complexity. Still no need for a CLI, a database, or any of those nasty, complex things.

Switching cards after a swipe, storing and loading data, and tracking swipes can all be done with some fairly basic Jquery and JSON, hard-coded on the client side.

For the data-wonks amongst you, tracking right-and-left-swipes for each card is built into Washingtinder.html. Just switch out your Google analytics tracking string (i.e 'UA-XXXXX-Y') for mine in the template, and swipes will be automatically tracked as events, and attached to your cards.

# Questions?
Have a question about making use of Simplest-Swipe-Cards? 
[Shoot me an email](http://www.michaelsitver.com) and I'd be happy to help!
