Celebrities
-----------
* `\b(?i:B.*ber)\b` — Filter all references to the word Bieber. ([@justin](http://twitter.com/justin))

Jargon
------
* `RT @` — Old style retweets ([@jordanekay](http://twitter.com/jordanekay))
* `MT @` — Modified old-style retweet ([@MikeBeas](http://twitter.com/MikeBeas))

Spam
----
* `^(@\w *)+$` — Tweets consisting solely of @usernames ([@jordanekay](http://twitter.com/jordanekay))

Annoyances
----------
* `#[A-Za-z]{15,}` — #sentencesashashtags ([@jordanekay](http://twitter.com/jordanekay))
* `(@\w+,? ){4,}` — Tweets with four or more @usernames in a row (you have friends, we get it) ([@jordanekay](http://twitter.com/jordanekay))
* `\b\w+\*+\w\b` — Tweets censored for no f**king reason ([@jordanekay](http://twitter.com/jordanekay))
* `(?i)checked.*in` - I checked in at... ([@jonohunt](http://twitter.com/jonohunt))
* `\n{3,}` — Tweets with 3 or more line breaks. ([@justin](http://twitter.com/justin))
* `^\.@` — Out of context public replies. ([@grahamwetzler](http://twitter.com/grahamwetzler))
* is my new jam – No one cares what your new jam is PLEASE SHUT UP GOSH ([@MikeBeas](http://twitter.com/MikeBeas))
* is my insanely catch song of the day ([@MikeBeas](http://twitter.com/MikeBeas))

Irrelevance
-----------
* `IE ?[0-9]+` — Internet Explorer ([@jordanekay](http://twitter.com/jordanekay))

Duplicate mentions
-----------
Mute your own @name (as a keyword, NOT a muted person), including the @ sign. This will remove all of your mentions from your main timeline, confining them to the mentions tab so you don't have to see them twice (or see only half of a conversation with someone you don't follow in your main timeline) ([@MikeBeas](http://twitter.com/MikeBeas))

SXSW
-----------
* `(?ism)^(?=.*?\bSXSW\b)(?=.*?\bpanel\b).*$` — Tweets containing 'SXSW' and 'panel' (case insensitive)

Persistent
-----------
* `(?i)(timezone|time.*zone).*(retweet|rt)` - Timezone RT ([@jonohunt](http://twitter.com/jonohunt))

* `(?i)(in.*case|if).*you.*missed.*it` - In case you missed it… ([@jonohunt](http://twitter.com/jonohunt))

* ICYMI - Shorthand for 'in case you missed it' ([@MikeBeas](http://twitter.com/MikeBeas))


Replies
-----------
* `^@` - mute tweets that begin with @, "replies" ([@khaled](http://twitter.com/khaled))

* `^(?i)(@name)` - mute replies to a specific person ([@khaled](http://twitter.com/khaled))

Ego Stroking
-----------
* `(?i)dribbble.*(last.*night|earlier)|(last.*night|earlier).*dribbble` - I @dribbbled earlier/last night ([@jonohunt](http://twitter.com/jonohunt))

* `(?i)popular.*page` - Popular page (*"I made the Popular Page on @dribbble"* ) ([@jonohunt](http://twitter.com/jonohunt))

* `(?i)followers.*on.*(dribbble|twitter)` - *"I've got xxx followers on @dribbble/Twitter"* ([@jonohunt](http://twitter.com/jonohunt))

Topical
-----------
* `(?i)ipad.*mini.*|.*mini.*ipad` - iPad mini ([@jonohunt](http://twitter.com/jonohunt))

* `(?i)dock.*connect(o|e)r` - Dock connector (iPhone 5) ([@jonohunt](http://twitter.com/jonohunt))

* `(?i)app.*net` - App.Net ([@jonohunt](http://twitter.com/jonohunt))

* `(?i)twitter.*(api|1.1)|api.*(twitter|1.1)|1.1.*(twitter|api)` - Twitter's new 1.1 API ([@jonohunt](http://twitter.com/jonohunt))

Arabic
-----------
* `#[\S]*[ضصثقفغعهخحجشسيبلاتنمكةءظطذدزروىأإآئؤ][\S]*` - mute Arabic tags ([@khaled](http://twitter.com/khaled))
                                                      - 
* `[ضصثقفغعهخحجشسيبلاتنمكةءظطذدزروىأإآئؤ]` - Mute Arabic tweets ([@khaled](http://twitter.com/khaled))

Stating the obvious
----------
* `(?i)((new|change).*avatar)|(avatar.*(new|change))` - *"Look, I changed my avatar"* ([@jonohunt](http://twitter.com/jonohunt))
