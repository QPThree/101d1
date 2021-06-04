# Local Storage

## In this Article

[Brief History](#topic1)

[HTML5 Storage](#topic2)

---

<a name="topic1"></a>

## Brief History

Web Apps have had a weak point regarding storage.  Back in the day, when cookies were the only way to store data, it really wasn't an option due to the downsides of cookies and using them for user data.

Microsoft introduced *DHTML Behaviors* which contained *userData*. userData allowed for up to 64KB of data to be stored per domain.

In 2007, Google's Gears allowed unlimited amounts of data to be stored per domain via an embedded SQL Database.

Unfortunately, each way of storing user data on webapps was different, with different allotments, on different browsers.

<a name="topic2"></a>

## HTML5 Storage

HTML5 Storages is a way for webpages to store key/value pairs locally. The data then persists after the user has navigated away from the page or application. The latest version of virtually every browser is HTML5 storage compatible.

Keys are strings and have values that can be paired with them. One can access a value by calling the key in the localStorage as one would call an index in an array.

The storage amount with HTML5 Storage is 5 megabytes.

An important note is that values are also stored as strings. As such, when accessing the values via their paired key, you'll need to coerce the string into your desired datatype (e.g. parseInt()).

~ QP3

[Home](../README.md)

Information put into my own words came from *The Past, present, & Future of Local Storage for Web Applications*
