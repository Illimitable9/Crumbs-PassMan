## **Crumbs PassMan:** The open source, secure password manager.

### Warning:
The project is currently in no usable state as of now, as it is in the alpha phase. By using Crumbs PassMan Alpha, you risk data breaches occuring on your system.
(side note: as of writing this, the project is so unusable that i have not put the code up yet. i keep developing on git while forgetting to actually share the code i make.)

### Why Crumbs?
if you are an android user, check when your camera or mic was last used by google play services developer features. why does play services need my mic for developer features? i dont even have developer mode enabled.

if you are an iphone user, i dont need to make you stop using google, as i will never release an ios client for as long as i live.

do you know which password manager doesnt track you? thats right, crumbs (and probably a few others). it doesnt use any analytics software at all. it even encrypts your passwords using various methods.

### And the security practices in question?
https (obviously)
very long sha256/512 (preference) totp used for encrypting data in-transit that works automatically, that changes seed after a specified period of time (default is 1 day, old seed is active until the new seed is confirmed)
each password file encrypted with a separate keyfile, accessible via the device that added the password file or a recovery usb
some other stuff i have yet to think of

### How do I recover lost data?
that's the neat part, you dont (hopefully).

### Oh crumbs, my server is down.
that's too bad.

### What about passkeys?
coming soon™, definitely before the release.

### Where are the files?
on my pc until i remember to commit. (im typing this readme on my phone, im in a foreign country atm)
