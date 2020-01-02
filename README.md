# ESP8266-TADO
Directly sends offset to Tado via HTTPS every 5 minutes

Written for ESP12e and DHT22 using platformio / vscode

This code is potentially buggy, and could lock you out of your Tado account

It's probably a bad idea to use many of these at once, as the effect of them trying to connect at the same time is untested...

Inspired by https://community.tado.com/en-gb/discussion/2800/trvs-horribly-inaccurate-any-suggestions?

Those pesky Tado TRV's are bloody inaccurate, Jon created this to try & counter that by introducing an external temperature sensor using an ESP8266 & DHT 22 temp sensor. 
I've added to it as the temp sensors seem to pick up anything more than an flies fart and the temp changes, so i've delayed the update time and added an offset margin.

Potentially even more buggy than Jon's version, but working. :s
