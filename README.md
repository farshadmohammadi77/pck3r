



# pck3r :

![Screenshot](screenshot/pck3r.png)

this program created for novice in linux   and can handle almost things in ubuntu and all distributions  based on  debian(package manager : "apt")...
this program , create by amzy0(M.Amin azimi.K) and can change under GPL3 license ...
you can send me a pull request in github : https://github.com/amzy-0/pck3r and features will be added to pck3r soon ...
good luck...

# logo :

    尸⼕长㇌尺

# GUI logo :

![GUI logo](icon/pck3r-logo.png)


# about pck3r :

    -----------------------------------------
    |                                       |
    | pck3r : It is a versatile program and |
    |                                       |
    | you avoid using useless commands and  |
    |                                       |
    | it is written for Ubuntu...           |
    |                                       |
    -----------------------------------------


# tree of the pck3r project :
        


            pck3r/
            ├── bin
            │   ├── pck3r
            │   ├── pck3r-terminal-emu
            │   └── pck3r-terminal-emu-tilix
            ├── core.c
            ├── icon
            │   └── pck3r-logo.png
            ├── includes
            │   └── requires.h
            ├── install-pck3r-ubuntu
            │   ├── installer
            │   └── installer.c
            ├── LICENSE
            ├── Makefile
            ├── pck3r-terminal-emu.c
            ├── pck3r-terminal-emu-tilix.c
            ├── preinstallRequirements.sh
            ├── README.md
            ├── screenshot
            │   └── pck3r.png
            ├── source-updator-for-dev
            └── updator-pck3r
                ├── updator
                └── updator.c


# compile all c file :

$ make


*preinstall Requirements :*


$ ./preinstallRequirements.sh






"install" command :

    $ pck3r install "somthing" :
    {
            nodejs,
            python3pip,
            java,
            wine,
            ohmyzsh,
            or ...
    }

"clear" command :

    $ pck3r clear:
    {clear your terminal }

"iso" command :

    $ pck3r iso 32/64  "somthing":
    {
        mint,
        fedora,
        gentoo,
        or ...
    }

"dwn" command :

    $ pck3r dwn "https/http://somthing"
    {dwn is downloader for pck3r }

"sys" command :

    $ pck3r sys update
    (update your oprating system)

    $ pck3r sys upgrade
    (upgrade your oprating system)

    $ pck3r updgr
    (both, update and upgrade (full upgrade))

"term" command :

    $ pck3r term
    (command for run, pck3r terminal emulator)

"google" command :


    $pck3r google <browser> <search section(word1 word2 word3 ...)
    (quick google search ...)
    (like this : $ pck3r google firefox word1 word2 word3 to wordX)

"tilix" command :


    $ pck3r tilix
    (tilix terminal ...)


"dotnet" command : 

    $ pck3r install dotnet
    (installing .NET (dot net ) C0RE, ASP, MCS compiler , ...)    


"pkg" command :


    $ pck3r pkg <package name>"
    (search for packages ...)"



# install pck3r  global :


$ cd install-pck3r-ubuntu/

$ ./installer


# update pck3r :


$ cd updator-pck3r/

$ ./updator


# local running :

$ cd bin/

$ ./pck3r <commands>
