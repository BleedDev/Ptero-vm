# Ptero-VM

Root-Instance inside of pterodactyl's docker container with Proot.

## ✨ Features

- Root well, inside the docker container.
- idk whatelse

## 💁‍♀️ How to use

- first make a server (js/py server)
- then Grab the `installer.py` or `installer.js` file
- then go to startup section of the server and name it `installer.py` (if u made python server and downloaded the installer.py file) or `installer.js` (if u made js server and downloaded the installer.js file)
- now start the server and it will install the files for you and run PteroVM
- you're done

## ✨ Preinstalled Packages

- Python & PIP

- NodeJS & NPM

- Java

- Go

- Htop

- Nofetch

- Nano

- Screen

- Gotty

- Ngrok

- Xmrig

- Playit

## ✨ Patched bugs

- Systemctl being annoying has been fixed!

## ✨ Addons

 __GoTTY:__
 
 _GoTTY is a simple GoLang based command line tool that enables you to share your terminal(TTY) as a web application. It turns command line tools into web applications._

- to run gotty just type `gotty -p <port> -w bash`in your terminal.

- now it will be up and running, and it will show the ip and port of it in the console. copy paste it in ur browser and there you have remote terminal with gotty

__Xmrig:__
 
 _Xmrig is a CPU crypto mining software which is easy to manage_

- to run Xmrig just type `xmrig -o rx.unmineable.com:3333 -a rx -k -u <coin_here>:<Wallet_address_here>.<worker_name_here> -p x` ie: `xmrig -o rx.unmineable.com:3333 -a rx -k -u SHIB:0xDEcDA3d4bfA4E614A383c17F4E01DD8E0DA9abFE.my_cpu_miner -p x`  in your terminal and continue the steps. if you have any doubts [[Read this docs!]](https://xmrig.com/docs/miner)

__Playit:__
 
 _Playit is a tunneling software to portforward your server  to custom domains other than the numeric ip_

- to run playit just type `playit` in your terminal and continue the steps. if you have any doubts [[Read this docs!]](https://playit.gg/support/run-on-linux/)

__Ngrok:__
 
 _Ngrok is a tunneling software to portforward your server  to custom domains other than the numeric ip_

- to run ngrok just type `ngrok http <port>` or `ngrok tcp <port>`ie: `ngork tcp 22`  in your terminal and continue the steps. if you have any doubts [[Read this docs!]](https://ngrok.com/docs)


## ✨ Note

**Please use a host which have atleast 5GB disk space or it will messup the installation.

_this script is configured to only support pterodactyl panel, if u want to make it support something like replit fork it and edit it._

**This script is for educational purposes, we are not responsible for anything that happens.**
