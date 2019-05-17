# GetOrganelleDep

Binary files of [GetOrganelle v1.6.0+](https://github.com/Kinggerm/GetOrganelle) dependencies.

## Installation

No other compiling required. Just download this repository to GetOrganelle without changing the directory tree.  

    # Supposing you installed GetOrganelle at ~/Applications/bin
    
    cd ~/Applications/bin/GetOrganelle
    
    git clone git://github.com/Kinggerm/GetOrganelleDep

Then follow the [installation instruction for GetOrganelle](https://github.com/Kinggerm/GetOrganelle#installation). You could delete or keep the sub-folder of another operation system, for example, `rm -r GetOrganelleDep/macOS` if your system is linux. 

<b>Alternatively</b>, you could also finish above things for your linux system as:

    # Supposing you installed GetOrganelle at ~/Applications/bin
    
    # Supposing your system is linux, otherwise change the 'linux' into 'macOS'
    
    cd ~/Applications/bin/GetOrganelle && mkdir GetOrganelleDep && cd GetOrganelleDep
    
    svn co https://github.com/Kinggerm/GetOrganelleDep/trunk/linux

GetOrganelle would not add those dependencies to the $PATH thereby not influence your own usage. For example, if you already installed SPAdes v3.6.2, after installing GetOrganelle the spades version for your system would still be v3.6.2 while only GetOrganelle uses its own [SPAdes version](https://github.com/Kinggerm/GetOrganelleDep/linux/SPAdes/share/spades/VERSION). So you might also remove any of the dependency folder if it was already available in your system and you would like GetOrganelle to use yours as well, although not suggested for compatibility consideration.