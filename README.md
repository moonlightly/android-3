Domination
==========

Getting Started
---------------

To get started with domination, you'll need to get
familiar with [Git and Repo](http://source.android.com/source/using-repo.html).

To initialize your local repository using the domination trees, use a command like this:

    repo init -u git://github.com/Domination-42/android.git -b Domination

To sync up:

    repo sync


How to build?
-------------

Building is pretty easy the only thing you need to know is the name of the device you're building for.
For example i'm going to build for the Samsung Galaxy Nexus the gsm edition called 'maguro'.
This is the only thing you'll have to do:

    ./build.sh <device_name>


How to get a changelog of the commits between your latest build and now?
------------------------------------------------------------------------

it is easy just execute this command:

    ./build.sh MM/dd/yyyy

for example if i've build my latest release on april 24 of 2013 and i want a changelog for my release i just do this:

    ./build.sh 04/24/2013


