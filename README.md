Pushover for Weechat
====================

Send a Pushover message ( cf. https://pushover.net ) to your Android or iPhone 
in the event of private messages or highlights occuring in Weechat.

Install
-------

Load the pushover-weechat.rb plugin into Weechat. Place it in the
~/.weechat/ruby directory:

    /ruby load pushover-weechat.rb

It also requires a Pushover account.

Setup
-----

Set your Pushover user key.

    /set plugins.var.ruby.pushover-weechat.userkey 123456789abcdefgh

Options
-------

plugins.var.ruby.pushover-weechat.userkey

The user key for your Pushover service.
Defaults to an empty string and must be set for pushover-weechat to
work.

Author
------

James Turnbull <james@lovedthanlost.net>
https://github.com/jamtur01/pushover-weechat

slightly modified by policecar
https://github.com/policecar/pushover-weechat


License
-------

Apache 2.0

