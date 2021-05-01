WSL
=================================================================================
.. contents:: **Daftar Isi**

Enable WSL
---------------------------------------------------------------------------------

**Referensi**

- `enable wsl <https://www.wikihow.com/Enable-the-Windows-Subsystem-for-Linux>`_
- `install wsl <https://docs.microsoft.com/en-us/windows/wsl/install-win10>`_
- `using wsl in windows 10 <https://blog.netsarang.com/1884/using-the-linux-subsystem-in-windows-10/>`_


Reset Password
---------------------------------------------------------------------------------

::

		$ wsl --user root
		$ passwd 
		atau
		$ passwd username


**Referensi**

- `reset WSL password <https://askubuntu.com/questions/772050/reset-the-password-in-ubuntu-linux-bash-in-windows>`_

Mount Drive
---------------------------------------------------------------------------------

::

        sudo mount -t drvfs Y: /mnt/y



Mount Shared Drive
---------------------------------------------------------------------------------

::

        sudo mkdir /mnt/mountedshare
        sudo mount -t drvfs '\\servername\sharename' /mnt/mountedshare

Tampilan
---------------------------------------------------------------------------------
        
- `nice looking <https://medium.com/@Andreas_cmj/how-to-setup-a-nice-looking-terminal-with-wsl-in-windows-10-creators-update-2b468ed7c326>`_
- `wsltty: correct color in wsl <github.com/mintty/wsltty>`_
- `mount removable drives <https://www.howtogeek.com/331053/how-to-mount-removable-drives-and-network-locations-in-the-windows-subsystem-for-linux/>`_


		
