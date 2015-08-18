### ASSEMBLY LINE

Learning assembly language is the way to grok the machine and
eradicate magics.

### NOTES

All programs contained herein were compiled with:

```hla -main:_main -l"macosx_version_min 10.9" -l"lSystem" -l"no_pie" <program>```

### HLA INSTALLATION

For OSX:

* [Download HLA](http://webster.cs.ucr.edu).
* Extract the tarball to ```/usr```.
* Symlink the ```hla``` and ```hlaparse``` bins into your path.
* I have added the lib vars to my dotfiles, you could do:
```
hlalib=/usr/hla/hlalib 
export hlalib
hlainc=/usr/hla/include
export hlainc
```
* Now type ```hla``` - if all good, you can now compile code.
