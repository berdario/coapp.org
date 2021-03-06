---
layout: packages
---
A software package is a file that has been prepared in such a way that it contains all of the compiled 
code and metadata needed for it to be installed, updated or removed by an installer or package management
system.  In the case of CoApp, packages are the final output of a build process that produces 
Windows-optimized MSI files that can be installed, updated or removed by the Windows Installer (WiX) 
on Windows Servers. <br>

Another way to think about the packages produced by CoApp is that they are shallow forks of libraries
and applications that are maintained by communities of developers who make regular and frequent changes
to their code bases and whose code bases typically support multiple hardware architectures.  A
shallow fork is a snapshot of one node of the code base that can be optimized and built for
installation on a particular server with the intention of resynching the with the original code
base over short intervals.  Packages built using CoApp lend themselves to a consistent method
of installing, updating and removing software and staying up-to-date with changes to the software's
code base.



