horseshit
=========

**horseshit** is an easy-to-use command line program that blocks websites known to distract us from our work, which is forked from `leftnode/get-shit-done <https://github.com/leftnode/get-shit-done>`_.

Unlike **get-shit-done**, **horseshit** is implemented in Python only, with both 2.x/3.x compatibility. **horseshit** is also a PyPI package, so that it can be installed and updated via *pip* or *easy_install*.

Project homepage: http://www.soimort.org/horseshit

Fork me on GitHub: https://github.com/soimort/horseshit



Installation
------------

**Using the PyPI package**

Install the PyPI package::

    $ pip install horseshit

or::

    $ easy_install horseshit

**Using Git**

Clone the Git repository::

    $ git clone git://github.com/soimort/horseshit.git

After cloning this repository, you may want to put it in your *$PATH* and ensure it is executable.



Usage
-----

**1. Setting horseshits**:

*horseshits* is a no-brainer plain text file contains a load of horseshits that may distract you from work, line by line::

    plus.google.com
    twitter.com
    reader.google.com
    reddit.com

Also there is an example of what *horseshits* should be like in: *horseshits.example*.

On \*nix systems, put your *horseshits* into::

    /etc/horseshits

You can simply use the example I provided if you'd like::

    sudo cp horseshits.example /etc/horseshits

Or start writing your own::

    sudo vi /etc/horseshits

On Windows, put it into your own user directory::

    .config/horseshits

**2. To get-shit-done**:

Execute *get-shit-done* as root because it modifies your hosts file and restarts your network daemon::

    $ sudo get-shit-done work

**3. To no longer get-shit-done**::

    $ sudo get-shit-done play



Additional Tips
---------------

You can, of course, use *get-shit-done* with your *crontab*, to control your work time and play time during the day. Whatever, I should say self-control is always the best.



Acknowledgement
---------------

Thanks to Vic Cherubini, the original author of **get-shit-done**.

Thanks to myself. It finally comes to me that I have to stop my goddamned procrastination and increase focus NOW - for a proper work efficiency.

Shit kickin' productivity!