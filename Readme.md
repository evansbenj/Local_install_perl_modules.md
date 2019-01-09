# How to do a local install of a perl module

Download module and enter directory.  Type this:
```
perl Makefile.PL INSTALL_BASE=path_to_directory
```
then

```
make
```
then
```
make install
```
and in the perl script use this to call the local directory
```
use lib '/home/ben/project/ben/2018_Austin_XB_genome/Bio--Kmer/lib/';
use Bio::Kmer;
```
