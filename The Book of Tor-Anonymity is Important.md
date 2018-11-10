## Anonymity is Important

Let's begin with something useful.

In order to use Tor, you ideally need a browser that can access it. The Tor Browser on desktop platforms, formerly known as the Tor Browser Bundle, and the Orfox Browser with the Orbot app on Android are the suggested browsers. Why? Tor takes anonymity seriously.

The four log entries below are from 4 browsers that are using Tor.

#### Brave:
`127.0.0.1 - - [10/Nov/2018:12:56:19 +0000] "GET /favicon.ico HTTP/1.1" 404 209 "http://irvdwucxcq6kb2nm.onion/" "Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/70.0.3538.77 Safari/537.36"`

#### Firefox:
`127.0.0.1 - - [10/Nov/2018:13:00:58 +0000] "GET /favicon.ico HTTP/1.1" 404 152 "-" "Mozilla/5.0 (X11; Linux x86_64; rv:62.0) Gecko/20100101 Firefox/62.0"`

#### Tor Browser
`127.0.0.1 - - [10/Nov/2018:12:57:27 +0000] "GET /favicon.ico HTTP/1.1" 404 152 "-" "Mozilla/5.0 (Windows NT 6.1; rv:60.0) Gecko/20100101 Firefox/60.0"`

#### Orfox
`127.0.0.1 - - [10/Nov/2018:13:04:53 +0000] "GET / HTTP/1.1" 200 396 "-" "Mozilla/5.0 (Android; Mobile; rv:52.0) Gecko/20100101 Firefox/52.0"`

The first log entry is from the Brave browser (https://www.brave.com) which has Tor built in into their Private Window mode. This is a really neat concept, but you gain a lot of information about the person using this browser and that makes them stand out. You can see which website that I am trying to access. You can see that I am running 64-bit Linux. You can also see that I am running a browser based on Chrome. None of these things tell you exactly who I am but they fingerprint me as someone who stands out. The goal of anonymity is it blend in with the rest of the internet.

The second entry is normal unmodified Firefox running on Tor. This is a little better. It almost completely matches the entry for Tor Browser, except that it gives away my operating system and it is a not running the same version as the Tor Browser.

I didn't change to a Windows PC to test the Tor Browser, all versions will always report the same information. It will always report that it is being used in Window since it is the most widely used operating system. It's important to keep it up to date not only to apply bugfixes but to keep in line with all of the rest of the Tor Browser users.

The final entry is for Orfox. Yes, you can see that I am running it on Android as it is based on the Firefox app for Android. This is a bit of a negative. Preferably you would want it to appear to be the same as the normal Tor browser but there is probably a trade off.  All copies of Orfox, no matter the device or version of Android, should look the same. However in order to get mobile versions of websites suitable for a mobile device, the browser needs to identify itself as a mobile browser. We'll discuss more about fingerprinting in a later chapter.
