Features
========

- Supports client certificates and thus can be registered on a server by an admin or even can register itself if the server allows it.
- As of version 0.10.x it is available in English, German and Bavarian, see :ref:`here <settings_language>`.
- Bot automatically adjusts its bitrate to fit the servers bandwidth limitation.
- Stream audio from an MPD.
- Support for :ref:`plugins <plugins-label>`.
- Can download music, for example from Youtube or other websites.
- Can search for music on Youtube or other websites.
- Streaming of internet radio.
- Live changing of bitrate or volume.
- Audio ducking – the bot lowers the playback volume if a user speaks.
- Supports both CELT and Opus codec for maximum compatibility even on old Mumble servers <1.2.4.
- No need for a web interfaces to control the bot. Everything can be done with text commands on your Mumble server.
- Support for whitelist of users who are only able to control the bot. Superusers are treated as being on the whitelist automatically.

For a complete list of features you must try the bot yourself. Write ``.help`` to your own bot and have fun :)

.. seealso::

  If you hesitate whether setting up the Mumble-Ruby-Pluginbot is worth it you may connect to `Natenoms Mumble-Server`_ in order to test one of the bots there. Just ask someone for an admin and a temporary registration on the server.

  .. _Natenoms Mumble-Server: https://www.natenom.com/mymumbleserver/
