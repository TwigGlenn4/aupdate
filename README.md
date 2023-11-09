# aupdate
Command line wrapper for updating Linux software with apt
# Usage
Aupdate combines apt's options for updating repositories, upgrading packages, removing unused automatically installed packages, and removing old version packages from the cache.
### Options
```-a --ask``` Ask for confirmation before installing updates.<br>
```-s --summary``` Summarize package changes after install.<br>
```-g --gui``` Sends a desktop notification if a reboot is required to finish updates. When used with ```--summary``` option the summary is opened in a text editor.<br>
```-h --help``` Outputs these usage options.<br>
# Installing
### Install for all users
Copy to PATH
```bash
sudo cp aupdate /usr/local/bin/aupdate
```
Mark executable
```bash
sudo chmod +x /usr/local/bin/aupdate
```

### Install for one user
Copy to PATH
```bash
cp aupdate ~/bin/aupdate
```
Mark executable
```bash
chmod +x ~/bin/aupdate
```
