# aqua-singularity-recipe
The files and license included here (besides the recipe), came from [AQUA](http://www.bork.embl.de/Docu/AQUA/1.1/)

This recipe installs all the pieces necessary to run AQUA, and makes everything available for easy usage.

Using the built image is as easy as:
`singularity exec aqua.simg AQUA.tcl foo.fasta`

The resulting output files will be dumped into the current working directory.

You can see a quick list of the tools I've installed with their respective help by running:
`singularity run aqua.simg`

The full list of what you have is:
 - AQUA.tcl
 - normd
    - normd
    - normd_sw
    - normd_range
    - normd_aln
    - normd_subaln
    - normd_aln1
 - mafft
    - mafft 
    - mafft-distance
    - mafft-einsi
    - mafft-fftns
    - mafft-fftnsi
    - mafft-ginsi
    - mafft-homologs.rb
    - mafft-linsi
    - mafft-nwns
    - mafft-nwnsi
    - mafft-profile
    - mafft-qinsi
    - mafft-xinsi
  - muscle 
    - muscle 
  - rascal
    - rascal 

All of rascal's pieces are under `/usr/bin/rascal1.34` and can be accessed from there, but they're not automagically in the default path.


