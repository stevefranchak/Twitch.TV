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
* Improve the "Stream Search" textfield
    - Retain the search string (it's annoying to have to retype everything when making an error)
    - Have an 'X' icon to the right of the textfield to cancel the search and empty the textfield
* Look into ways to improve the video player (?)
* Improve the UI look-and-feel to be more alike Twitch's site

### Second Stage

* Add Browse category for Videos
* 



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
