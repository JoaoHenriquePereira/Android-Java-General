# Android-general

Android-general is my repo for all the Android related widgets / snippets that I have enjoyed producing in the past, some are incomplete projects or they are simply snippets that I thought I'd might find useful in the future.

# Projects

## CustomSeekBarPlay

This is a small project in which I played around customizing a simple SeekBar to represent a whole calendar interface by adding all kinds of custom objects to it.

## SlideJSONParse

SlideJSONParse was also a small project in which I tried to produce a simple app with the "hyped" sliding panel design (similar to the Facebook app of the time) with 2 main fragments:

* FeedFragment.java
* MyPageFragment.java

FeedFragment loaded a simple JSON based stream with "Posts" from users and presented them as a typical Facebook-User-Activity-Stream-like design. The JSON stream was loaded via REST request from a simple webserver.

Additional features include also:

* Asynchronous update of the JSON feed
* "Endless" scroll or "Progressive data" scroll similar to many recent web apps

## TagAssistant

This is a Fragment manager snippet that I created when developing another app "Taginator". It successfully interconnects several data display fragments and loads data from a SQLlite database.

## WiFlow

WiFlow was my first app released in the Google store. It's a facade algorithm which tried to assist android users connecting to other Wi-Fi networks requiring manual input of credentials every time.

The project was officially plugged off on January 2014 due to lack of time and interest to keep up with the permanent changes occurring with all the networks supported.