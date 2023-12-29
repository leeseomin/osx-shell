# osx-shell
osx shell script


### poweroff :  Turn off the Mac with the "poweroff" command in the terminal.
```

echo '#!/bin/bash\nsudo shutdown -h now' > poweroff

chmod +x poweroff

sudo mv poweroff /usr/local/bin/

```
