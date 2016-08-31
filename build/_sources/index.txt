V.I.C.T.O.R.
============
**Versatile Intelligent Construct Trained for Online Research**

.. image:: ../images/logo.jpeg
    :width: 200px
    :alt: Victor's logo

Victor is my personal assistant.
Written in Python, his heart resides in a Raspberry Pi 2, but he can listen from various Arduino devices and sensors
placed inside my house.

We can divide Victor in two main parts:
    - The Core
    - various Modules

Above all theese, there is a script which starts a Victor instance, simply called by
::
    python victor.py [COMMAND]

There is another script (hey_vic.py), always running in background, constantly listen from commands imparted by a
microphone. When a command is recognised by the Speech-to-Text Engine,
he simply call a Victor instance using the victor.py program.

Victor speaks. Obviously. A personal assistant who do not speak a single word is useless. He used a linux very light
program, espeak, configured to produce a robotic voice.

Lets talk about the modules. Here is a list of what Victor can do:
    - Speak (I've already told that)
    - Listen (online and offline Speech-to-Text engines, depending on the accuracy I need for that task)
    - Tell the time
    - Check the weather
    - Check for new emails
    - Check for new Facebook Notifications
    - Check for events in Google Calendar
    - Set an alarm (which plays a song while Victor speaks all the above)
    - Google Search
    - Play songs from Spotify
    - Display my Twitter timeline
    - Tweet on his own account
    - Check if someone enter or exit the main house door, greeting me or my friends.
    - Connect to my Android phone to do stuff with it

In future, I'm planning to add:
    - Facial Recognition
    - Auto watering my plants
    - Set an alarm in my house
    - maybe a robotic arm...
    - maybe even walk... ... ...