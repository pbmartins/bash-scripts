# ChangeDNS
```
changedns [interface] [option]
```

The program will list the available interfaces, so you can choose which one to change.
This works on both Linux and OSX.
Place the script into ```~/bin``` and edit your ```.bash_rc``` (Linux) / ```.bash_profile``` (OSX) and add the following:
```
changedns() {
    . changedns "$@"
}
```

### Allowed functions
***Change to Google DNS servers***
Adds Google DNS nameservers to your DNS configuration.

***Remove all current DNS configurations***
Restore default DNS nameservers provided by your ISP.

### Usage
Simples use ```changedns``` and follow the instructions.
If you're currently using a Linux machine, you can use ```changedns [option]```.
If you're on OSX, you can use ```changedns [interface] [option]```.
