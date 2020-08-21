## youtube-dl  
  
youtube-dl is a command-line program to download videos from YouTube.com  
  
requires:    
apt: ```apt install ffmpeg```  
yum: ```yum install ffmpeg```  
pacman: ```pacman -S ffmpeg```  
  
PIP Package  
```sudo -H pip3 install --upgrade youtube-dl```  
  
Automatic install/update:
```
bash -c "$(curl -LSs https://github.com/dfmgr/rep/raw/master/install.sh)"
```
Manual install:
```
mv -fv "$HOME/.config/youtube-dl" "$HOME/.config/youtube-dl.bak"
git clone https://github.com/dfmgr/youtube-dl "$HOME/.config/youtube-dl"
```
  
  
<p align=center>
  <a href="https://wiki.archlinux.org/index.php/youtube-dl" target="_blank">youtube-dl wiki</a>  |  
  <a href="https://ytdl-org.github.io/youtube-dl/index.html" target="_blank">youtube-dl site</a>
</p>  
