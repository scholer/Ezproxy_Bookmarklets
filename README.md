# Ezproxy_Bookmarklets
Bookmarklet to re-open current page via Harvard University Library EzProxy server. More ezproxy hosts can be added upon request!

Instructions:

1. Drag the link below to your browser's bookmark bar.
2. Open a journal page, e.g. <a href="http://www.pnas.org/content/98/15/8608.full">http://www.pnas.org/content/98/15/8608.full</a>, then click the bookmarklet in your browser bar. You should now get the page via HUID's ezproxy server.

That's it. For reference, if you have a decent browser, you can also just add the bookmarklet directly by specifying the javascript as the bookmark's URL.

Note that for Mobile Chrome on Android/iOS you cannot use bookmarklets from the "bookmarks" window. Instead, select the address bar and start to type the name of the bookmarklet, e.g. "HUID EzProxy Bookmarklet". When the bookmarklet shows up in the list of suggestions, just press it and you should get the re-direct.


## Bookmarklets:
(Use the html file to get functional links; github markdown doesn't accept javascript in anchor href)

Harvard University Library: <a href="javascript:(function(){ezproxy_host='.ezp-prod1.hul.harvard.edu';window.location.hostname=window.location.hostname+ezproxy_host})();">HUL EzProxy Bookmarklet (Harvard)</a> - requires a Harvard University ID (HUID) or eCommons login.
```javascript
javascript:(function(){ezproxy_host='.ezp-prod1.hul.harvard.edu';window.location.hostname=window.location.hostname+ezproxy_host})();
```


Aarhus University Library / Statsbiblioteket: <a href="javascript:(function(){ezproxy_host='.ez.statsbiblioteket.dk';window.location.hostname=window.location.hostname+ezproxy_host;window.location.port=2048})();">AU EzProxy Bookmarklet (Statsbiblioteket)</a> - requires a Aarhus University ID or Statsbiblioteket login.
```javascript
javascript:(function(){ezproxy_host='.ez.statsbiblioteket.dk';window.location.hostname=window.location.hostname+ezproxy_host;window.location.port=2048})();
```