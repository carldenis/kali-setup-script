# Kali Setup Script

Prepares Kali for a pentest by enabling session logging, installing tools, and making common configuration changes

<img alt="XFCE + Gnome" src="https://user-images.githubusercontent.com/20261699/77855493-cd481680-71be-11ea-8019-20681c643b0d.PNG" width=500>

## NOTE: THIS SCRIPT ASSUMES YOU ARE RUNNING AS ROOT (LIKE IN THE OLD DAYS)
## NON-ROOT USERS ARE NOT SUPPORTED

## One-liner:
(don't forget to reboot after the script finishes :)
~~~
curl -k -s https://raw.githubusercontent.com/carldenis/kali-setup-script/master/kali-setup-script.sh | bash
~~~

## Full feature list:

1. Enables details logging of terminal sessions
	- Including ALL OUTPUT (saved to ~/Logs)
2. Installs the following:
	1. CrackMapExec (from GitHub)
	2. Impacket (from GitHub)
	3. Bloodhound (from GitHub)
	4. EAPhammer (from GitHub)
	5. patator (network brute-force tool)
	6. PCredz
	7. Gowitness
	8. EavesARP
	9. bettercap
	10. docker
	11. Firefox (official non-ESR version)
	12. Chromium
	13. Sublime Text (optional)
	14. BoostNote
	15. golang (plus environment)
	16. zmap
	17. LibreOffice (optional)
	18. htop
	19. Remmina
	20. gnome-screenshot (optional)
	21. realtek-rtl88xxau-dkms (ALFA wireless drivers)
3. Updates system
4. Disables auto-lock
5. Enables tap-to-click
6. Initializes Metasploit database
7. Installs wallpaper

# credits

Initial script by blacklanternsecurity;

Wallpaper by Rudy and Peter Skitterians from Pixabay; Thank you! ; https://pixabay.com/photos/donald-duck-spotlight-comic-cartoon-498512/

