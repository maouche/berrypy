# Download software:
git clone https://github.com/maouche/berrypy



# URL for download "url.txt" and "code.txt":
https://berrybox.yacinem.com/app/12345678




# Config Raspberry to run the script when reboot system:

## In terminal colle this to open crontab:
crontab -e

## And add this line in crontab:
@reboot cd /home/pi/berrypy/dist/main && ./main
