# osx-shell script 


### poweroff :  Turn off the Mac with the "poweroff" command in the terminal.
```

echo '#!/bin/bash\nsudo shutdown -h now' > poweroff

chmod +x poweroff

sudo mv poweroff /usr/local/bin/

```

### running Processes info

```
top
```



###  "zam"  : enter sleep mode  "zam" command in the terminal.
```
# Create the 'sleep' script with the command to enter sleep mode
echo '#!/bin/bash\npmset sleepnow' > zam 

# Make the 'sleep' script executable
chmod +x zam

# Move the 'sleep' script to /usr/local/bin/ to make it globally accessible
sudo mv zam /usr/local/bin/
```
