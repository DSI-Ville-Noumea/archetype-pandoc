# ${appName}-pandoc
${appName} user book

# Prérequis système

```
sudo apt-get install make git pandoc

# puis les fontes et styles :
sudo apt-get install texlive-xetex
sudo apt-get install texlive-fonts-recommended
sudo apt-get install texlive-fonts-extra
sudo apt-get install texlive-latex-base
sudo apt-get install texlive-latex-extra
sudo apt-get install lmodern

```

# Compilation

```
git clone https://github.com/DSI-Ville-Noumea/${appName}-pandoc.git
cd ${appName}-pandoc
make
ls -la build
```

