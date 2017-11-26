+++
title = "A Brief Guide To DuckDuckGo"
date = 2015-03-07T17:08:55+01:00
draft = false
tags = ["search engine", "duckduckgo", "guide"]
categories = ["blog"]
Og_Image = "ddg_logo.jpg"
thumbnailImage = "ddg_logo.jpg"
+++

Or why you should be using it even if you don't care about [privacy](http://donttrack.us/) or don't know what a [search engine bubble](http://dontbubble.us/) may be.

<img src="ddg_logo.jpg" width="1000" height="600" alt="DuckDuckGo  Logo">

It's in no way comprehensive nor "the best of". Just what I find more useful.

### Time


* `days between today and 02/28/2013` = 16 days. Unfortunately, this uses the US month/day/year format
* `18:30 to 19:25` = 55 minutes
* `february calendar` = print the calendar for this year's february

### Travel


* `weather` = weather for your current location
* `80100` = search for the map of your postal code. Finds also matching codes in other countries. Or you can specify `80100 Germany` to  get the result you want straight away
* `florence sunrise` = when does the sun rises in Florence? Here too it works with in the local language
* `temp in new york` = current temperature in New York

### Numbers and Math


* `uuid` = generate a random unique identifier
* `roman numeral MCCXXII` = convert the roman numeral in arabic. That's 1222, btw
* `md5 whatever` = calculate md5 sum of `whatever`
* `sha whatever` = calculate sha sum of `whatever`. Works with `sha256` and `sha512` too
* `goog` = company and stock data (Google)
* `roll 4d12` = simulate rolling 4 d12 dices. D&amp;D fans, rejoice!
* `average 10, 33, 54, 70` = 41.75
* `square root of 84` =  9.16515138991168
* `is 765 prime` = find whether a number is prime or not
* `random number` = generate a random number
* `45 farenheit in celsius` = 7.222. It works also as `45 F to C` (shorter)

### Currency and Finance


* `100 usd to eur` = 74.28€
* `usd vs eur` = conversion values between $ and €

### Words


* `0110100001100101011011000110110001101111 to ascii` = binary to ascii conversion
* `hello in binary` = convert hello to binary. Accepts ascii, numbers and hex
* `anagram the ship was sailing` = anagram a phrase. Works in any language but results are rarely meaningful
* `lorem ipsum` = generate random text
* `detect language merci` = that's french, of course. Works pretty well with local dialects too
* `define oxen` = definition for oxen
* `spell incospicuous` = check spelling
* `random word` = generate a random, english, word. It's possible to specify the range of characters length with `random word 5-9`
* `chars little test` = how many characters in `little test`?
* `related to cat` = words related to `cat`
* `synonyms for cat` = find synonyms

### Travel


* `AZ 107` = flight status by flight code. I found this to be somewhat unreliable but 99% of the queries the first link is the right one
* `distance paris to london` = 342km. Works in the local language too (Koln instead of Cologne, Roma instead of Rome etc.)
* `time in honolulu` = what time is it in Hawaii?

### Entertainment


* `monumension album by Enslaved` = info on an album
* `Jesus Saves, I Spend song by St. Vincent` = info on a song
* `songs by Metallica` = most popular songs on Last.fm from Metallica
* `imdb Young Frankenstein` = info on a movie
* `xkcd` = get the latest xkcd comic

### Cooking


* `1 tsp to gram` = how many grams is a teaspoon?
* `calories in 100 gr of cottage cheese` = 81 calories. Works with both Imperial/Metric systems
* `carbs in rice` = how many carbohydrates on average in a rice portion? Works also with fibers, saturated fat, magnesium etc. For more precise calculations use `how much fiber in 100gr of salmon`
* `nutrition in a kiwi` = detailed nutritional facts about Kiwis. The fruit, that is
* `how to mix a Americano` = how to prepare an Americano?

### Geek


* `@Donearm` = shows twitter profile
* `#duckduckgo` = Twitter hashtag search
* `google+ Gianluca Fiore` = search for G+ profiles
* `:D` = meaning of the :D emoticon. Not that many are supported but at least the most common are
* `password 9 strong` = generate a random password of 9 characters
* `expand http://dlvr.it/2rwGVR` = expand a shortened url
* `qrcode http://www.google.com` = generate a qrcode for Google homepage
* `is duckduckgo.com up?` = is our favourite duck up?
* `ip address` = show your current IP address
* `useragent` = show your browser User-Agent
* `unicode €` = unicode codes and name for the any symbol
* `U+123a` = what symbol corresponds to this Unicode code?
* `&#33;` = decode HTML entities
* `reddit luajit` = search Reddit posts about LuaJit
* `port 23` = TCP port information
* `hex color code for dark grey` = get RGB, HSL and CMYB values for a colour
* `#368798` = find colour from its HEX code
* `urlencode still$` = urlencode a string (still%24 in this case). More escape codes with `url escape`
* `bitly url` = shortens url with bit.ly
* `gravatar email` = find Gravatar for an email address
* `public dns` = list common public DNS servers
* `64.200.12.10` = IP address lookup

### \*nix


* `man ctags` = manpage for ctags
* `crontab 10 0 * 1 *` = when a task is being scheduled by cron?
* `epoch` = time since the Unix epoch
* `12343435 time` = convert a Unix epoch to date. Also `unix time 12343435`

### Programming


* `http status 102` = reference for http status codes. More generally, it accepts various query for many languages. For example, `lua function`, `c #define`, `python urllib2` all return, more or less, what you'd expect
* `emacs C-t` = Emacs reference
* `html span` = html entities reference
* `git cherry-pick` = git manpage
* `lua jobs` = Github Jobs search (only 1 for lua, me sad...)

# !Bang Syntax

These are a bit different since they don't make queries on DuckDuckGo but use other websites to search *into*. In general, it's like using `site:http://www.mysite.com query`, only with far less keystrokes.  
There are a whole bunch of them. Like, [a lot](https://duckduckgo.com/bang.html). Do browse that list, I'm sure there are many sites that you use to browse to in order to make a search with their internal search form but with these you can do it directly from DuckDuckGo main page. Extremely handy when you already know where to look.

My favourites are:

* `!tumblr` = search on Tumblr
* `!h33t` or `!torrent` or `!torrentz` = torrent search. You know, legal stuff.
* `!firefox` = search Firefox add-ons
* `!vim` = search on vim.org. I use it all the time to know what a new plugin does
* `!appbrain` = Android app search
* `!gist` = Gists search. Some great gems can be found among gists
* `!github` = repository search on Github
* `!python` and `!python3` = search in Python (2 or 3) documentation
* `!xdaf` = xda-developers.com forum search
* `!so` = Stackoverflow. Best way to get a quick answer to a programming problem
* `!unix` = search in \*nix source code
* `!distro` = lookup a Linux distribution on distrowatch.com
* `!archlinux`, `!archwiki` and `!aur` = search, respectively, on Archlinux forum, wiki and among AUR packages
* `!amit` and `!amuk` = Amazon search (It and Uk)
* `!cstheory` = computer science questions and answers
* `!lonelyplanet` = Lonely Planet
* `!tripadvisor` = TripAdvisor
* `!bmaps` or `!map` or `!osm` = Map searches (Bing, Google and OpenStreet)
* `!urban` = slang words search on Urban Dictionary
* `!allmusic` = Allmusic
* `!define` = Define a word
* `!spanishdict` = From spanish to english
