fforward (for Android)
=======================

Hey!

fforward is an open source Android app that will help people micro-crowdfund. $1- to $100 is our domain.

Users will log on and see interesting projects and products as they scroll.

![Imgur Image](http://i.imgur.com/hbAX4BH.jpg)

# Our Ticket System

We use github issues to write tickets. Tickets are called Feature, or Design. If you see one that looks interesting, you are welcome to click it and try to write the code. Right now we are fixing the design. The fonts + colors are uninspiring. THat needs to change.

## [fforward issues](https://github.com/Microflow/fforward-android/issues)



# fforward Back-End

We have forked RedReader, an open source client for Reddit. Running on the Reddit API allows us to validate fforward for free. We will simplify and change Reddits design until it looks different from the standard Reddit UI. We use Reddit to serve a JSON feed for the prototype. Users do not need to have a Reddit account to use fforward.

For the prototype, we will take a JSON feed from [this subreddit](https://www.reddit.com/r/fforwardTaiwan/). As we expand, we'll add more cities and countries. Each country or city will have its own subreddit. 

Here is an example of a [web-app that uses a re-designed Reddit API](https://codepen.io/Teeke/live/NpZyJB). The user does not know they are using Reddit.

Once we fix the design and get some users, we hope to become a Taiwanese charity!



## Fforward was forked from an original open source project called Red Reader.

Building
--------

RedReader is built using Gradle. Several dependencies are required (and
listed in build.gradle), but these are handled automatically if you use
Gradle.

Detailed instructions on building RedReader using IntelliJ IDEA are in
[BUILD.md](BUILD.md).


License
-------

RedReader is licensed under the GPL, version 3. A copy of the license is
included in [LICENSE.txt](LICENSE.txt).

Bitcoin donations are welcome and accepted at the following address:
`1874wapGxDo2vEp4avisda4gx3SCjsHCQJ`


Thanks
------

Thanks to:

* tomorrowkey.jp, for the [GIF decoder](https://code.google.com/p/android-gifview/) (Apache License 2.0)
* Apache, for various libraries
* The [Jackson JSON processor](http://jackson.codehaus.org/)
* [Joda](http://joda-time.sourceforge.net/)
* [/u/fosterbuster](http://www.reddit.com/user/fosterbuster) for the Danish translation
* [/u/balducien](http://www.reddit.com/user/balducien) and [/u/andiho](http://www.reddit.com/user/andiho) for the German translation
* [remil19](https://github.com/remil19) for the French translation
* [Husam Bilal](https://github.com/husam212) for the Arabic translation
* [Juanma Reyes](https://github.com/jmreyes), [moshpirit](https://github.com/moshpirit), and Andrés Hernández for the Spanish translation
* [Martin Macko](https://github.com/LinkedList) for the Czech translation
* [klenje](https://github.com/klenje) for the Italian translation
* [Beleg-Cuthalion](https://github.com/Beleg-Cuthalion) for the Dutch translation
* [tjernquist](https://github.com/tjernquist) for the Swedish translation
* [Badita Viorel-Octavian](https://github.com/vooctavian) for the Romanian translation
* [András Lengyel-Nagy](https://github.com/lna91) for the Hungarian translation
