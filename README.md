## youtube-dl  
  
youtube-dl is a command-line program to download videos from YouTube.com  
  
Automatic install/update:

```shell
bash -c "$(curl -LSs https://github.com/dfmgr/youtube-dl/raw/master/install.sh)"
```

Manual install:
  
requires:

Debian based:

```shell
apt install ffmpeg
```  

Fedora Based:

```shell
yum install ffmpeg
```  

Arch Based:

```shell
pacman -S ffmpeg
```  

MacOS:  

```shell
brew install youtube-dl
```

PIP Package:  

```shell
sudo -H pip3 install --upgrade youtube-dl
```  

```shell
mv -fv "$HOME/.config/youtube-dl" "$HOME/.config/youtube-dl.bak"
git clone https://github.com/dfmgr/youtube-dl "$HOME/.config/youtube-dl"
```
  
<p align=center>
  <a href="https://wiki.archlinux.org/index.php/youtube-dl" target="_blank" rel="noopener noreferrer">youtube-dl wiki</a>  |  
  <a href="https://ytdl-org.github.io/youtube-dl/index.html" target="_blank" rel="noopener noreferrer">youtube-dl site</a>
</p>  
