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
* `(?i)checked.*in` — I checked in at... ([@iconaholic](http://twitter.com/iconaholic)) 
* `\n{3,}` — Tweets with 3 or more line breaks. ([@justin](http://twitter.com/justin))

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
* `(?i)timezone.*(retweet|rt)` — Timezone Retweet ([@iconaholic](http://twitter.com/iconaholic))

* `(?i)in.*case.*you.*missed.*it` — In case you missed it… ([@iconaholic](http://twitter.com/iconaholic))


Replies
-----------
* `^@` - mute tweets that begin with @, "replies" ([@khaled](http://twitter.com/khaled))

* `^(?i)(@name)` - mute replies to a specific person ([@khaled](http://twitter.com/khaled))

Ego Stroking
-----------
* `(?i)dribbble.*(last.*night|earlier)|(last.*night|earlier).*dribbble` — I @dribbbled earlier/last night ([@iconaholic](http://twitter.com/iconaholic))

* `(?i)popular.*page` — Popular page (*"I made the Popular page on @dribbble."*) ([@iconaholic](http://twitter.com/iconaholic))

Topical
-----------
* `(?i)ipad.*mini.*|.*mini.*ipad` — iPad mini  ([@iconaholic](http://twitter.com/iconaholic))

* `(?i)dock.*connect(o|e)r` — Dock connector (iPhone 5)  ([@iconaholic](http://twitter.com/iconaholic))

* `(?i)app.*net` — App.Net  ([@iconaholic](http://twitter.com/iconaholic))

Arabic
-----------
* `#[\S]*[ضصثقفغعهخحجشسيبلاتنمكةءظطذدزروىأإآئؤ][\S]*` - mute Arabic tags ([@khaled](http://twitter.com/khaled))
                                                      - 
* `[ضصثقفغعهخحجشسيبلاتنمكةءظطذدزروىأإآئؤ]` - Mute Arabic tweets ([@khaled](http://twitter.com/khaled))
