Celebrities
-----------
* `(?i:B.*ber)` — Filter all references to the word Bieber. ([@justin](http://twitter.com/justin))

Jargon
------
* `RT @` — Old style retweets ([@jordanekay](http://twitter.com/jordanekay))

Spam
----
* `^(@\w *)+$` — Tweets consisting solely of @usernames ([@jordanekay](http://twitter.com/jordanekay))

Annoyances
----------
* `#[A-Za-z]{15,}` — #sentencesashashtags ([@jordanekay](http://twitter.com/jordanekay))
* `(@\w+,? ){4,}` — Tweets with four or more @usernames in a row (you have friends, we get it) ([@jordanekay](http://twitter.com/jordanekay))
* `\b\w+\*+\w\b` — Tweets censored for no f**king reason ([@jordanekay](http://twitter.com/jordanekay))

Irrelevance
-----------
* `IE [0-9]+` — Internet Explorer ([@jordanekay](http://twitter.com/jordanekay))

Duplicate mentions
-----------
Mute your own @name (as a keyword, NOT a muted person), including the @ sign. This will remove all of your mentions from your main timeline, confining them to the mentions tab so you don't have to see them twice (or see only half of a conversation with someone you don't follow in your main timeline)