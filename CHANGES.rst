Release Notes
=============

v0.11 - Radio buttons
---------------------
*  Added support for radio buttons.
*  Corrected transparent icons for *OSX*.


v0.10 - Changed Xlib backend library
------------------------------------
*  Changed *Xlib* library.
*  Corrected test with incorrect parameter.


v0.9 - Submenus
---------------
*  Added support for nested menus.


v0.8 - Platform independent API and checkable
---------------------------------------------
*  Added method to explicitly update menu to enable support for other platforms.
*  Added support for *AppIndicator* backend.
*  Re-added native clickability for *OSX*.
*  Added support for check boxes.


v0.7 - Dynamic menus
--------------------
*  Added support for dynamically generating menu item properties when a popup
   menu is displayed.
*  Display the default menu item distinctly.
*  Changed the menu item API slightly.
*  Corrected logging on Windows.


v0.6 - Simplified API
---------------------
*  Removed explicit default action parameter ``on_activate``.
*  Allow terminating the application with *ctrl+c* on *OSX*.
*  Added basic logging.


v0.5 - Menu support
-------------------
*  Added support for popup menus.
*  Corrected bug which prevented stopping the icon on *Windows*.
*  Corrected documentation.


v0.4 - GTK+ 3 support
---------------------
*  Added support for *GTK+* on *Linux*.


v0.3.5 - Corrected import errors
--------------------------------
*  Propagate import errors raised on Linux to help troubleshoot missing
   ``Xlib`` module. Thanks to Lance Kindle!
*  Properly declare ``six`` as a dependency.
*  Declare ``python3-xlib`` as dependency on *Linux* for *Python 3*.


v0.3.4 - Corrected Python 3 issues on Xorg
------------------------------------------
*  Make sure that ``pystray`` can be used on *Python 3* on *Xorg*.
*  Make sure the release making script runs on *Python 3*.


v0.3.3 - Corrected encoding issues
----------------------------------
*  Make sure building works even when default encoding is not *utf-8*.
*  Corrected issue with click selector on *OSX*.


v0.3.2 - Universal wheel
------------------------
*  Make sure to build a universal wheel for all python versions.


v0.3.1 - No-change packaging update
-----------------------------------
*  Do not package an old version of ``pynput``.


v0.3 - Proper Python 3 Support
------------------------------
*  Corrected Python 3 bugs.
*  Made ``Icon.run()`` mandatory on all platforms.


v0.2 - Initial Release
----------------------
*  Support for adding a system tray icon on *Linux*, *Mac OSX* and *Windows*.
