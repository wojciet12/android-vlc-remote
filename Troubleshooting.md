# On your PC running VLC media player #
  1. Make sure that VLC is running.
  1. Make sure that the VLC web interface is enabled (_View_ -> _Add Interface_ -> _Web Interface_). Please note that this step must be repeated each time VLC is started.
  1. Make sure that a firewall is not blocking access to the server.
### VLC v2.1.0 and later ###
  1. [Set Lua HTTP password](Setup.md)
  1. You may need to restart VLC after changing the Lua HTTP password
### VLC v2.0.8 and earlier ###
  1. Edit the `.hosts` file.
    * On UNIX/Linux, the file is `/usr/share/vlc/http/.hosts` or `/usr/share/vlc/lua/http/.hosts`
    * On Windows the file is`C:\Program Files\VideoLAN\VLC\http\.hosts` or `C:\Program Files\VideoLAN\VLC\lua\http\.hosts` (or in some cases, `C:\Program Files (x86)\...`).  On Windows Vista and Windows 7, you may need to change the file permissions before editing the file or alternatively run Notepad as an admistrator.
    * On Mac OS X, the file is `VLC.app/Contents/MacOS/share/http/.hosts` or `VLC.app/Contents/MacOS/share/lua/http/.hosts`
  1. You may need to restart VLC after changing the `.hosts` file

# On your Android device #
  1. Make sure that you are connected to the correct Wi-Fi network
  1. Make sure that you can connect to the Web Interface (e.g., `http://192.168.1.XXX:8080`) from the web browser on your Android phone or tablet. If this does not work, then there is a problem with your network connection and/or server configuration.

# Still having problems? #
Check if what you are seeing is a [known issue](http://code.google.com/p/android-vlc-remote/issues/list?q=Type%3DDefect).  If it is not, then please [submit a new bug report](http://code.google.com/p/android-vlc-remote/issues/entry) with a detailed description of the problem you are experiening.
> .