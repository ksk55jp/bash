### Pupose
To record dot files 


actual file|purpose|description
-----------|-------|-------------
bashrc | to be ~/.bashrc | resource file for login shell
profile | to be ~/.profile | resource file for non-login shell
alias | to be ~/.alias | aliases


### Once arrived, setup by below commands
```
cd ~
mkdir bin
cd !$
git clone https://github.com/ksk55jp/bash.git
cd bash
ln -nfs bashrc ~/.bashrc
ln -nfs profile ~/.profile
ln -nfs alias ~/.alias
```
