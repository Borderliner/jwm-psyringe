#What is this?<br>
This is my own configuration file for <a href="http://joewing.net/projects/jwm/" target="_blank">JWM</a> (Joe's Window Manager)<br>
It consists of a config file (.jwmrc), and a wallpaper (.wallpaper.png).<br>
I've included a script file (install.sh) to install this config, plus it's necessary components.<br><br>

#How do I install this?<br>
Clone this repo, cd into it, execute `./install.sh` to run the script (DO NOT RUN IT AS ADMIN, IF YOU DO, IT WILL INSTALL TO /root/.jwmrc)<br>
It is <b>STRONGLY RECOMMENDED to install Xfce components</b>, which is prompt during the installation process.<br><br>

#Key Bindings<br>

Alt + Tab => Switch to next window<br>
Alt + F4 => Close Window<br>
Alt + Ctrl + D => Show Desktop<br>
Alt + F1 => Show Main Menu<br>
Alt + F2 => Show Window's Menu (`Launch Application` instead of this)<br>
Alt + F10 => Maximize<br>
Alt + F11 => Make Window Fullscreen<br>
Alt + Ctrl + RightArrow => Switch to the Right Desktop<br>
Alt + Ctrl + LeftArrow => Switch to the Left Desktop<br>
Alt + Ctrl + UpArrow => Switch to the Up Desktop<br>
Alt + Ctrl + DownArrow => Switch to the Bottom Desktop<br>
Alt + Ctrl + T => Start Terminal<br>
Alt + Ctrl + X => Start XKill<br>
Ctrl + Shift + Escape => Show Task Manager (xfce4-taskmanager)<br><br>

#Keyboard Setup<br>

If you want to change the keyboard layout, open the .jwmrc file and navigate to line 166 and 175. Change the `ir` to whatever you like (`ir` is Iran, I use this for myself)<br>
If you wish to change the repeat rate, open .jwmrc file, go to line 165 and 174, change the rates there.<br>
Edit .xxkbrc to change flag settings<br><br>

<a href="mailto:hajianpour.mr@gmail.com">Borderliner<a>, 2016

