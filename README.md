# Applications apt-get install notes

## use apt-get
Developers can add a new entry pointing to OS source files and then use `apt-get` to install some common applications or libraries.

## Command Example

```bash
vim /etc/apt/sources.list.d/local.list
//Add the following line to the file:
deb [trusted=yes] http://47.89.252.251:8000/ubuntu24.04 ./

```
## Supported Applications and Tools
- Firefox
```bash
sudo apt-get update
sudo apt-get install firefox
```
- Chrome
- LibreOffice
