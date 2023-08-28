# my_vault
  `$ git clone https://github.com/malefficient/000_my_vault my_vault`
## Getting started in my_vault

## Initialize the submodules 
`git submodule init`
Submodule 00_Meta (https://github.com/malefficient/00_Meta.git) registered for path 00_Meta

`git submodule update`
Submodule path '0010_Meta': checked out '5d08a413d120671c6426bd7f447980bc832d7830'

If that went well you should have a plain vanilla obsidian vault that is split across two separate git repos.
The first repo (your repo), you can make all the changes you want!


## The 00_Meta repo
A second repo should have been downloaded into ./00_Meta
This is *my* repo, which you cannot make changes to. 

But what if you want to link to (or reference) my work? Is there an elegant solution that doesnt depend on some subtle implementation detail within obsidian itself?  I'm not sure, but i bult this [[00_Meta_Xref_tests]] file to investigate!

[[Admonition]]


