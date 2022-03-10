### Do nothing when lid is closed.
To disable Ubuntu doing anything closing the laptop lid:

Open the /etc/systemd/logind.conf file in a text editor as root, for example,

 sudo -H gedit /etc/systemd/logind.conf
If HandleLidSwitch is not set to ignore then change it:

 HandleLidSwitch=ignore
Make sure it's not commented out (it is commented out if it is preceded by the symbol #) or add it if it is missing.

### Markdown tutorial
 - https://github.com/tholman/tutorial-markdown
 - https://github.com/tal-baum/dynamic-markdown

### Ubuntu battery saver
 - https://www.omgubuntu.co.uk/2019/05/slimbook-battery-optimizer-ubuntu
