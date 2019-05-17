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

## Citation

Please denote the version in your manuscript for reproducible science.

GetOrganelle: Jian-Jun Jin*, Wen-Bin Yu*, Jun-Bo Yang, Yu Song, Ting-Shuang Yi, De-Zhu Li. 2018. GetOrganelle: an easy and fast toolkit for de novo assembly of accurate organelle genomes. bioRxiv, 256479. [http://doi.org/10.1101/256479](https://www.biorxiv.org/content/early/2018/03/14/256479)

Please cite the dependencies if they are used:

SPAdes: [Bankevich, A., S. Nurk, D. Antipov, A. A. Gurevich, M. Dvorkin, A. S. Kulikov, V. M. Lesin, S. I. Nikolenko, S. Pham, A. D. Prjibelski, A. V. Pyshkin, A. V. Sirotkin, N. Vyahhi, G. Tesler, M. A. Alekseyev and P. A. Pevzner. 2012. SPAdes: a new genome assembly algorithm and its applications to single-cell sequencing. Journal of Computational Biology 19: 455-477.](https://www.liebertpub.com/doi/abs/10.1089/cmb.2012.0021)

Bowtie2: [Langmead, B. and S. L. Salzberg. 2012. Fast gapped-read alignment with Bowtie 2. Nature Methods 9: 357-359.](https://www.nature.com/articles/nmeth.1923)

BLAST+: [Camacho, C., G. Coulouris, V. Avagyan, N. Ma, J. Papadopoulos, K. Bealer and T. L. Madden. 2009. BLAST+: architecture and applications. BMC Bioinformatics 10: 421.](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/1471-2105-10-421)