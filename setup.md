---
layout: default
---

Here are the instructions to install Git, a text editor, and R + RStudio

# Git Setup

If you do not have a GitHub acount please make one here: https://github.com/

Taken from the [software-crapentry git installation instructions](https://carpentries.github.io/workshop-template/#git)

### Windows

[Video Tutorial](https://www.youtube.com/watch?v=339AEqk9c-8)

1. Download the Git for Windows [installer](https://gitforwindows.org/).
2. Run the installer and follow the steps below:
    1. Click on "Next" four times (two times if you've previously installed Git). You don't need to change anything in the Information, location, components, and start menu screens.
    2. **Select "Use the nano editor by default" and click on "Next".**
    3. Keep "Use Git from the Windows Command Prompt" selected and click on "Next". If you forgot to do this programs that you need for the workshop will not work properly. If this happens rerun the installer and select the appropriate option.
    4. Click on "Next".
    5. Keep "Checkout Windows-style, commit Unix-style line endings" selected and click on "Next".
    6. **Select "Use Windows' default console window" and click on "Next".**
    7. Click on "Install".
    8. Click on "Finish".
3. If your "HOME" environment variable is not set (or you don't know what this is):
    1. Open command prompt (Open Start Menu then type cmd and press [Enter])
    2. Type the following line into the command prompt window exactly as shown:
    ```
    setx HOME "%USERPROFILE%"
    ```
    3. Press [Enter], you should see `SUCCESS: Specified value was saved.`
    4. Quit command prompt by typing `exit` then pressing [Enter]

This will provide you with both Git and Bash in the Git Bash program.

### MacOS

[Video Tutorial](https://www.youtube.com/watch?v=9LQhwETCdwY)
**For OS X 10.9 and higher**,
install Git for Mac by downloading and running the most recent "mavericks" installer from [this list](https://sourceforge.net/projects/git-osx-installer/files/).
Because this installer is not signed by the developer,
you may have to right click (control click) on the `.pkg` file,
click Open,
and click Open on the pop up window.
After installing Git, there will not be anything in your `/Applications` folder,
as Git is a command line program.

**For older versions of OS X (10.5-10.8)**
use the most recent available installer labelled "snow-leopard" available [here](https://sourceforge.net/projects/git-osx-installer/files/).

### Linux

If Git is not already available on your machine you can try to install it via your distro's package manager.

For Debian/Ubuntu run `sudo apt-get install git` and for Fedora run `sudo dnf install git`.

# Text editor

### Windows

nano is a basic editor and the default that instructors use in the workshop. It is installed along with Git.

Others editors that you can use are [Notepad++](https://notepad-plus-plus.org/)
or [Sublime Text](https://www.sublimetext.com/).
**Be aware that you must add its installation directory to your system path.**
Please ask your instructor to help you do this.

### MacOS

nano is a basic editor and the default that instructors use in the workshop. See the Git installation video tutorial for an example on how to open nano. It should be pre-installed.

Others editors that you can use are [BBEdit](https://www.barebones.com/products/bbedit/) or [Sublime Text](https://www.sublimetext.com/).

### Linux

nano is a basic editor and the default that instructors use in the workshop. It should be pre-installed.

Others editors that you can use are Gedit, Kate or Sublime Text.

# R

### Windows

[Video Tutorial](https://www.youtube.com/watch?v=q0PjTAylwoU)

Install R by downloading and running [this .exe file](https://cran.r-project.org/bin/windows/base/release.htm)
from [CRAN](https://cran.r-project.org/index.html).

Also, please install the [RStudio IDE](https://s3.amazonaws.com/rstudio-ide-build/desktop/windows/RStudio-1.2.1511.exe).
Note that if you have separate user and admin accounts, you should run the installers as administrator (right-click on .exe file and select "Run as administrator" instead of double-clicking).
Otherwise problems may occur later, for example when installing R packages.

### MacOS

[Video Tutorial](https://www.youtube.com/watch?v=5-ly3kyxwEg)

Install R by downloading and running this [.pkg file](https://cran.r-project.org/bin/macosx/R-latest.pkg) from CRAN.
Also, please install the [RStudio IDE](https://download1.rstudio.org/desktop/macos/RStudio-1.2.1335.dmg).

### Linux

You can download the binary files for your distribution from CRAN.
Or you can use your package manager (e.g. for Debian/Ubuntu run `sudo apt-get install r-base`
and for Fedora run `sudo dnf install R`). Also, please install the [RStudio IDE](https://www.rstudio.com/products/rstudio/download/preview/).
