# Team Solar - SMEZA PCB Repository

This is the repository for the PCB for the SMEZA. 

Code for the SMEZA should not be stored here - put those files in the [Team-Solar](https://github.com/kyperrone/Team-Solar) repo. 

We are using KiCad 7 for this project, as well as the following extensions:
- Freerouting extension, provided by the Official KiCad Repository. 
- Bounti's JLCPCB extension. This is in a [separate repository](https://github.com/Bouni/kicad-jlcpcb-tools) that must be added. 


# Explaination of Contents 
`smeza_pcb` - This folder contains the KiCad project files for the SMEZA PCB. 

`footprints` - This folder contains all of the project specific footprints in a convenient location. The footprint names in this folder are less than useful, so there is a README file that indicates which file is for which component. 

`symbols` - This folder contains all of the project specific symbols and footprints. Each component has its own folder. 


# Getting Started with using this repo 
I don't know how familiar everyone is with Git so I'm going to say a few things that are probably obvious to more experienced users. 

The primary branch for this repo is `main`. 

Please don't commit directly to main; make a branch for your changes and then when you are done make a pull-request. 

When possible, it is preferred that you obtain this repo by cloning it. However, since most Valpo machines do not have git it may be necessary to download the files and then try to merge after the fact. This is another good time to use a branch incase things get messed up. It should be noted that the 4-machines in the team solar senior design space have git installed - just make sure to use the git-bash terminal. 

While the KiCad files are technically text files, because of the large scale of changes made by even small changes, best practice is probably to clobber everything in `main` with the contents of the newer branch. 

If you have questions about using git, talk to Joel. 