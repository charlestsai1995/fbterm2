# FbTerm - a fast FrameBuffer based TERMinal emulator for linux

## DESCRIPTION

FbTerm is a fast terminal emulator for linux with frame buffer device or VESA video card. Features include:

  * mostly as fast as terminal of linux kernel while accelerated scrolling is enabled
  * select font with fontconfig and draw text with freetype2, same as Qt/Gtk+ based GUI apps
  * dynamicly create/destroy up to 10 windows initially running default shell
  * record scrollback history for every window
  * auto-detect current locale and convert text encoding, support double width scripts like Chinese, Japanese etc
  * switch between configurable additional text encodings with hot keys on the fly
  * copy/past selected text between windows with mouse when gpm server is running
  * change the orientation of screen display, a.k.a. screen rotation
  * lightweight input method framework with client-server architecture
  * background image for eye candy

read man page [doc/fbterm.1.in](doc/fbterm.1.in) for usage help.
