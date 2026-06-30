# TwitchAdBypass
Userscripot to bypass ads on Twitch without loss of resolution. Please not there can be a slight delay at start of stream, and during ad trigger while script strips ads for the available streams.

Best used with the following Userscript managers:

* https://violentmonkey.github.io/
* https://www.tampermonkey.net/
* https://apps.apple.com/us/app/userscripts/id1463298887

**This userscrpt does not work with Greasemonkey.**

Known Extension Conflicts

* 7TV — may cause black screen / infinite buffering (#17)
* TwitchNoSub — handled automatically via workerStringReinsert, but older versions may conflict
* TTV-AB — running both simultaneously may cause duplicate ad blocking and errors. Use one or the other.
* Purple AdBlock — may conflict if both are active. Disable one.
* AdGuard Extra — operates at a different layer, can be used alongside without conflict

Credit goes to the following people, https://github.com/ryanbr/TwitchAdSolutions & https://github.com/pixeltris/TwitchAdSolutions

**Disclaimer** Authors, this Repot and it's owner are not responsible for breakage unrelasted to the use of this script. This is an opensource solution that can and must be read in its entireity before installing and using.
