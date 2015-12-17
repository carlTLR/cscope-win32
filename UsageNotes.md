  * Check the [Cscope site](http://cscope.sourceforge.net) for some hints about its usage.
  * If you want Cscope to restore a screen after exit, define the environment variable PDC\_RESTORE\_SCREEN.
  * To use inverted indices (_-q_ option) you need _sort_ utility. I am including one with the cscope archive ([here](http://cscope-win32.googlecode.com/files/UnxUtilsSrc.7z) is its source code). The utility can also be found on [UnxUtils](http://unxutils.sf.net) and [http://gnuwin32.sf.net](http://gnuwin32.sourceforge.net/packages/coreutils.htm). It should be in your _PATH_ before Windows dir because Windows has its own, incompatible sort utility.
  * If you have troubles with long file names (particularly containing spaces), try to use 8.3-names (they are displayed with _dir /X_ command).
  * Remember about _:help cscope_ in Vim.