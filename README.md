dvue
====

Mobile device testing for responsive layouts

dvue is a simple page that loads a remote site into an iframe.  There is no device emulation support,
alternate user-agent support, or any other fanciness.  This is purely a container to check responsive layouts
at various resolutions.

dvue is intended to remain as a standalone html file with the only external resource being jquery.  It is
intended to remain image free, using CSS to render devices and viewports.

# todo
 * add android phones
 * add ipad
 * add android tablets
 * add device chooser menu
 * add landscape resolutions
 * add device orientation control
 * add support for URL history
 * add support to intercept ctrl-r refresh and redirect to all viewports