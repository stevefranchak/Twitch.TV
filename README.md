# stevefranchak's fork of Twitch.TV
This project is a fork of [svennergy's pull request](https://github.com/svennergr/Twitch.TV) for replacing the iframe with HTML5 video in [PatrickRorth's Twitch.TV LG TV WebOS application](https://github.com/PatrickRorth/Twitch.TV). I forked off of svennergy's project due to the improvements that I saw with the changes that were made. I'm hoping to make some of my own personal improvements to the project that might be useful to others. 

## TODO

### First Stage

* Better accessibility
    - Better history management when using the Back button
    - Navigate the application without relying on the pointer with the remote control
    - Navigate the application with a USB keyboard
    - Start up streams by using Google's Cast API from other devices (feasibility research required)
* Lazy load list of games and channels (do not enforce a limit of 100 entries)
* Options to sort the list of games and channels
* Options to filter the list of games and channels
    - Channels
        - Filter on language
        - Filter on console, creative, etc.
* Improve the "Stream Search" textfield
    - Retain the search string (it's annoying to have to retype everything when making an error)
    - Have an 'X' icon to the right of the textfield to cancel the search and empty the textfield
* Look into ways to improve the video player (?)
* Improve the UI look-and-feel to be more alike Twitch's site

### Second Stage

* Add Browse category for Videos
* Add Browse category for Creative
    - Clicking on Creative under Games navigates the user to this page
* Add the ability to log into a user's Twitch account
    - No ads for Twitch Prime users (however, I don't see ads now with svennergy's changes - why?)
    - When logged in, add Browse category for Following
    - Add the "You Follow" collapsible sidebar to the right of the screen
    - Get near real-time notifications when a channel that the user follows goes live
    - Add the option to follow a channel
    - Add the option to jump to the user's channel from the left sidebar
* Research whether it's possible to use LocalStorage to "Follow" channels without having to log into an account
    - This would give all of the benefits as above except any Twitch Prime benefits and jumping to the user's channel
    
### Third Stage

To be fleshed out more, but includes:

* Add the ability to show the chat while watching a stream
* Add the ability to send messages in the chat via the on-screen keyboard or a USB keyboard

## Issues

* Installing the application via Developer Mode only has the app installed while Developer Mode is enabled. If Developer Mode is disabled manually or automatically when the session expires, the app is uninstalled. Please contact me if you have a way around this.


## Original License  
MIT License

Copyright (c) 2016 Twitch.TV for LG WebOS

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
