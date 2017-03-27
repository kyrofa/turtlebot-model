# How to build image

If you want to use the gadget snap from the store:

    $ sudo ubuntu-image -c stable -o turtlebot.img turtlebot-<arch>.model


If you want to use a local gadget snap:

    $ sudo ubuntu-image -c stable -o turtlebot.img turtlebot-<arch>.model --extra-snaps /path/to/gadget.snap
