# PufferPanelTemplates
Custom Templates for PufferPanel

## MusicBot
### Prerequisites

The following steps from the [manual](https://just-some-bots.github.io/MusicBot/installing/debian/) should be done before installing server from the template.

```
# Update system repositories
sudo apt-get update -y
sudo apt-get upgrade -y

# Install dependencies
sudo apt-get install git libopus-dev libffi-dev libsodium-dev ffmpeg -y
sudo apt-get install build-essential libncursesw5-dev libgdbm-dev libc6-dev zlib1g-dev libsqlite3-dev tk-dev libssl-dev openssl -y

# If using Debian Stretch or lower, you need to install Python too using...
sudo apt-get install python3.5 python3-pip -y
```

### Post Installation Steps
There are two files:
* config/options.ini
* config/permissions.ini

Please edit them according to the [manual](https://just-some-bots.github.io/MusicBot/using/configuration/)
