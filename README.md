# FreeBSD-WindowMaker-Autostart
Simple WindowMaker autostart for FreeBSD (dockapps launch script)

* This WindowMaker autostart script is FreeBSD centric
* Dockapps name, start order and parameters are obtained via the file 'dockapp_list' in the script directory.
* 'dockapp_list' file format is [dockapp name]:[dockapp arguments]
  Example:  wmeyes:-w -p '#000000'
* Pay attention to variable '$sleep_delay' and adjust as needed
* All printf are used for debug purpose only and can be deleted
