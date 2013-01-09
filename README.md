Ack-menu is a fork of Nikolaj Schumacher's [full-ack](https://github.com/nschum/full-ack). Full-ack is a great extension, bringing the power of ack to emacs. Although ack has much better default settings than grep, it still has many useful options that can be set on the command line. Just as one example, I often use the -q option, which treats the search string as a literal string instead of a regexp, so you can easily search for a string containing regexp tokens like * for example.

Full-ack exposes ack options via emacs variables. This makes it possible to change the option values, but it's too slow to lookup and change a variable value for a single search. Ack-menu solves this by hooking up a magit-style menu system to ack. This makes it incredibly easy to change the default settings for a custom search.

Ack-menu also has an improved ack output parsing mechanism, which fixes a few bugs that were present in full-ack.

Having used many different grep/ack modules, I think ack-menu is the best mechanism available for grepping through directories via emacs. Give it a try.

![Ack-menu screenshot](http://chumpage.github.com/ack-menu/screenshot.png)
