Google Reader API lib (unofficial)
==================================

This lib is a fork of [pyrfeed](http://code.google.com/p/pyrfeed/)

Docs
----

For documentation about the unofficial Google Reader API you can read [GoogleReaderAPI](http://code.google.com/p/pyrfeed/wiki/GoogleReaderAPI)

Quick Start
-----------

    import GoogleReader

    gr = GoogleReader.GoogleReader()
    l = ('mymail@google.com', 'mypassword')
    gr.identify(*l)

    #Example to subscribe to a new feed
    gr.add_subscription(url="https://gist.github.com/brutuscat.atom")


You can also modify and run the GoogleReader.test() method to see if everything is running smoothly.