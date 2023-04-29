# nucleus
sort of like a cell nucleus takes dna and makes proteins, I want this to take source code in python and make shell commands or .exes. 

A repo that can live on github and I can just clone it, have the functions, from anywhere, and it just works

* Maybe `git clone` is insufficient to set it all up. I'll have to make a setup script after all and this is all pointless. But I will have a better idea of how to structure things. Might work for some.

Goal 1: wolverine.py
* runs with 'wolverine' when I'm in CMD
* " in powershell
* " in bash on windows (should not need to navigate to mnt/c, should not need to do anything other than drop into wsl and it is available)
* Stretch goal: terminux on android, some way to use it from phone.
* Runs from current directory
* Never manage nvm, pip, python (I think this should all be baked into the repo. Because why bother any other way, you can never get away from the dependencies and versions, even if it's a module that is pip installed and pip takes care of that, that also leave me blind to what all happened and guessing whether it will work again later on: with other things installed / upgrade versions etc.)

* Then I'll go from there.

Some ideas:
* make up rules about which scripts are allowed or not. Like not everything that can run on laptop can run on phone, but idk. Also might need rules about being able to do one command after another, piping, being part of other python code, etc.
