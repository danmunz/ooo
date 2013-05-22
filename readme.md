The OOO Decider
===============

At some point, I got tired of writing long, elaborate OOO messages every time I was out of the office for a few days; most of that information should be reusable, and you should only need to change what's changed (updated contact info, etc.).

At the same time, I was also looking for a way to efficiently manage communication while OOO. People should:

* be able to contact me if (and _only_ if) there's a real emergency;
* try some of my alternate contacts in the absence of a real emergency; and
* be able to get in touch with me when I'm back if they really need to talk to me.

Getting all of this text into a single message in a readable way was a bit of a pain. So, I decided to style use the amazing @[akiany](https://github.com/akiany)'s JS decision wizard code into a decision tree people could use to decide what to do with me OOO. So now, instead of writing:

> Hi, I'm out of the office, but you can contact me here, unless you need to talk to Phil, in which case his phone number is 123-456-7890, but don't call Phil about X, email Janet about X, and her phone number is 987-654-3210

You can just write:

> Sorry, I'm out of the office. For more info, see [http://danmunz.github.io/ooo/](http://danmunz.github.io/ooo/)

This site also takes advantage of some great jQuery plugins:

* [Backstretch](http://srobbin.com/jquery-plugins/backstretch/) for nice-looking responsive background images
* [Scrollto](http://flesler.blogspot.com/2007/10/jqueryscrollto.html) for smooth scrolling and starting the page at the top each time
* [DetectMobileBrowsers](http://detectmobilebrowsers.com/) for when I include some fanicness that isn't supported/appropriate on mobile


Features
--------

* Defines a true 'emergency' and routes people with one to my emergency contact info.
* Provides a clear list of alternate contacts, with e-mail addresses encoded into HTML entities
* Offers download of an ICS file to prompt a visitor to email me when I'm back
