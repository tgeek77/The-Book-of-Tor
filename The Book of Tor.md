# The Book of Tor

For Larisa, my angel

The Dark Web is a scary place. – The Internet
No it isn't. – Me

## Introduction

I want to access DW, first time, don't know how at all. Please help

Please help I'm on a Samsung phone, what do i do to access the dw  do I have to download anything? Is my info safe on phone? What page do i start on? Heelp. Real discussions only pls

–Reddit User

Dear Reddit user,

I don't know you or where you are from. I don't know how old you are or your level education or really anything about you. This short book won't cover everything about Tor. It will also not talk down to you like you are five years old. I am assuming that you are a relatively intelligent human being who can read a book. First of all, it will answer your question. It will also help you understand what it is that you are asking and to dispel a lot of preconceived notions about what Tor is and isn't.

One final note, this is the only time that I will use the terms: “Dark Web”, “Deep Web”, “Marianas Web”. The “Dark Web” is the Tor Onion Router network, also known as Tor. The “Deep Web” is any service that can only be accessed by VPN or other routing means except Tor. Your company has an intranet for HR. That's the Deep Web. If you make your own network at home to stream movies to your TV, you've made your own Deep Web. Once you shine light on 
these terms, you realize that they are just click-bait and don't really describe anything useful. As for the Marianas Web, it is completely fiction.

## Begin at the Beginning

Let's begin with something useful. We'll do this in four parts for Windows, Linux, Mac, and Android users.

### Installing The Tor Browser

#### Windows

1. Go to: https://www.torproject.org/projects/torbrowser.html.en

2. Download the latest version for Windows

3. Run the installer

4. You will now see a new folder on your Desktop. Open that and run Tor Browser.

5. Click Connect

6. Congrats, you are on Tor!

7. Go to https://www.facebookcorewwwi.onion/ in the Tor Browser

#### Linux

1. Go to: https://www.torproject.org/projects/torbrowser.html.en

2. Download the latest version for Linux

3. Open a command line

4. Unzip the application. Replace xxxxxx with the current version that you downloaded

`tar -xvJf tor-browser-linux64-xxxxxx.tar.xz`

5. You will now see a new folder. Open that and run Tor Browser.

`cd tor-browser_en`

6. Run the application

`./start-tor-browser.desktop`

7. Click Connect

8. Congrats, you are on Tor!

9. Go to https://www.facebookcorewwwi.onion/ in the Tor Browser

#### Mac

1. Go to: https://www.torproject.org/projects/torbrowser.html.en

2. Download the latest version for Mac

3. Run the installer

4. You will now see a new folder on your Desktop. Open that and run Tor Browser.

5. Click Connect

6. Congrats, you are on Tor!

7. Go to https://www.facebookcorewwwi.onion/ in the Tor Browser

#### Android

1. Go to the app store and download the following two apps: Orfox 
   and Orbot. Both are from The Tor Project. Orbot is the Tor service. Orfox is the Android implementation of the Tor Browser. There are many "Dark Web" and "Onion" android apps and many of them are bogus and may steal your data or are just scams.

2. Start Orbot and connect to the Tor network.

3. Start Orfox

4. Go to https://www.facebookcorewwwi.onion/ in Orfox.



### What did we do?

In this section, we installed the Tor browser for the operating system of your choice. WIth the exception of Android, the Tor browser actually runs a copy of the Tor application inside of it which you can connect to as a socks proxy on port 9150. On Android, the Orbot app takes care of that for you.






