# M3D Fio
OctoPrint plugin for the Micro 3D printer
<br>
© 2015 Exploit Kings. All rights reserved.
<br>
<br>
You can install it with OctoPrint's built in plugin manager. The URL for that is '<a href="https://github.com/donovan6000/M3D-Fio/archive/master.zip">https://github.com/donovan6000/M3D-Fio/archive/master.zip</a>' or you can install it manually with the command 'pip install https://github.com/donovan6000/M3D-Fio/archive/master.zip'
<br>
<br>
<br>
If you're using Linux, the 90-m3d-local.rules needs to applied in order to avoid issues. You can apply it like this:

    mv ./90-m3d-local.rules /etc/udev/rules.d/
    sudo /etc/init.d/udev restart
