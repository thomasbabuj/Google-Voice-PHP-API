Google Voice PHP API
====================

An API to interact with Google Voice using PHP.

Currently the API can place calls, send and receive SMS messages, and
download transcriptions of voicemail.

Feel free to implement new functionality and send me your changes so
I can incorporate them into this library!

Note: Receiving SMSs and voicemails is mostly unnecessary via this API
since Google now allows SMSs to be forwarded to an email address. It is 
a better idea to parse those incoming emails with a script.

SMS and Voice Integration
=========================

For better SMS and voice integration with your web app, check out Tropo
at [tropo.com](http://tropo.com). Tropo is free for development, and you will get 
better results than using unsupported Google Voice API calls. 

Check out some [sample apps built with Tropo](https://www.tropo.com/docs/scripting/tutorials.htm)

Disclaimer
==========

This code is provided for educational purposes only. This code may stop working
at any time if Google changes their login mechanism or their web pages. You agree that
by downloading this code you agree to use it solely at your own risk.

License
=======

Copyright 2009 by Aaron Parecki
[http://aaronparecki.com](http://aaronparecki.com)

See LICENSE

