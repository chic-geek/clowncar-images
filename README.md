# Clowncar responsive images technique

Some simple responsive image testing using the 'clowncar technique'.
The idea is to load only the images that you **NEED** rather than everythiing being piped to the device in question which can sometimes lead to a super heavy website.

The trick is to use an `<object data="url/of/img.svg"></object>` element rather than an `<img src="">` element due to webkit and firefox security issues.

Useful URL's:
* http://www.smashingmagazine.com/2013/06/02/clown-car-technique-solving-for-adaptive-images-in-responsive-web-design/

* https://github.com/estelle/clowncar
