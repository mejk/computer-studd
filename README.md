# Random computer stuff

- Random notes on various computer issues, installation etc.  
- USE AT YOUR OWN RISK!
- The installations described on the pages have been tested but mileage may vary.

----------------------

## General

- [Cross platform (Linux, Windows, Mac) software](cross-platform-software.md)
  - Word processors, reference managers, graphics, communication, programming, etc.

## VNC, SSH, etc

- [VNC client and server installation](vnc-installation.md)
- [VNC client and server basic use](vnc-how-to-use.md)
- [SSH keys, config files and ssh agents](ssh-keys.md)

## Ubuntu

- [Installation of CUDA and Nvidia drivers & TensorFlow (Ubuntu 20.04 LTS)](ubuntu/cuda-and-nvidia-drivers.md)
  - TensorFlow 2 with & without GPU support using Docker.
- [Word processors with GUI: WPS Office and LibreOffice](ubuntu/word-processors-with-gui.md)
  - WPS Office with the extra fonts installed (instructions provided) is an excellent MS Office replacement with very high degree of compatibility.
  - LibreOffice connects well with JabRef reference manager, supports LaTeX math (via a plugin) and has great support for scalable vector graphics.
- [Ubuntu/Linux tips and tricks](ubuntu/ubuntu-tips-and-tricks.md)
- [Wipe out Windows and install Ubuntu only](ubuntu/new-computer-linux-only-win-preinstalled.md)
  - You can always install Windows in VirtualBox
- Dual boot Windows 10 / Ubuntu
- Java. How to check your current Java version? Like this: `java -version`. You may have/want different Java versions (JRE/Developmen Kit) on your computer. Here's how to switch between them: `sudo update-alternatives --config java`
- [System tools and related](ubuntu/system-tools.md)
  - git, package managers, application launchers...

## Windows

- [How to find your Windows licence key](windows-licence-key.md)
  - For example: if you wipe out Windows, you may still want to install it in VirtualBox and then you need the key (and you have already paid for it)
- [How to remove BitLocker](windows/bitlocker.md)
  - This may be important when creating a dual boot computer.
- WSL (Ubuntu shell) and GUI software
  - Works great when you install [Vcssrv](https://sourceforge.net/projects/vcxsrv/) or [Xming](https://sourceforge.net/projects/xming/)

