## Change ubuntu.css
`sudo gedit /usr/share/gnome-shell/theme/ubuntu.css`

## Used Theme 
*Adapta-Nokto-Eta*

## Icon theme - Dalisha
```
sudo add-apt-repository ppa:noobslab/icons
sudo apt-get update
sudo apt-get install dalisha-icons
```

## Solution for firefox dark input
https://www.mkammerer.de/blog/gtk-dark-theme-and-firefox/


1. Open about:config in Firefox
2. Create a new String value (right click), named `widget.content.gtk-theme-override`
3. Set a light GTK theme name as the value, i chose `Adapta-Eta`
4. Restart Firefox
