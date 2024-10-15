## AIO [Atsumeru](https://github.com/Atsumeru-xyz/Atsumeru) systemd service installation script for BASH

Download AIO script and run it (I strongly recommend that you run it as a non-root user):
```shell
curl -s https://api.github.com/repos/Atsumeru-xyz/Atsumeru-systemd/releases/latest | grep "browser_download_url.*install.sh" |  cut -d : -f 2,3 |  tr -d \" |  wget -q -O install.sh  -i - && \
chmod u+x install.sh && \
./install.sh
```

## Important points

- A user is created, in the user group on behalf of which the script for the service with the home directory /opt/atsumeru is launched.
- The content is supposed to be stored in the same directory (symlinks are supported).
- The script works on debian based distributions

[GitHub](https://github.com/Atsumeru-xyz/Atsumeru) for Atsumeru

All info is available on [Atsumeru](https://atsumeru.xyz/) website


## Acknowledgments

* [Atsumeru-xyz](https://t.me/atsumeru_app)
