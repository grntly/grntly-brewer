# grntly-brewer ¯\\\_(ツ)_/¯

![Build passing](https://img.shields.io/badge/Build-pass-brightgreen)
![Platform](https://img.shields.io/badge/Platform-MacOs-lightgrey)


grntly-brewer is a Proof of concept for slingle line clean installer script for new MacOS nodes



#how to use the mtbr brewer


# tl;dr;

Get the latest version of the script and run the install

    /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/grntly/grntly-brewer/refs/heads/main/mac_setup.sh)"

Delete zoom

    /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/grntly/grntly-brewer/refs/heads/main/uninstallers/remove-zoom.sh)"
    
Enter the credentials for the new user and have fun!

## How does this work

It gets the latest repo's of brew and install al the needed software for a person at this time!
After the install of the latest repos the script created userfiles for en set those for the user.
and at least the correct settings wil be deployed for a specific user.

## Features
- embedding application uninstallers in installer/checker
- .bashrc file create and edit
- .macos file create and edit
