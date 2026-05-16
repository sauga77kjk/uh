VIEW THIS TUTORIAL IN CODE SO THAT NEWLINES EXIST

tutorial:
install cloudflared and install the windows msi/exe
open cmd
type in "cloudflared tunnel --url http://localhost:8000"
wait then u should get
+--------------------------------------------------------------------------------------------+
|  Your quick Tunnel has been created! Visit it at (it may take some time to be reachable):  |
|  https://random-words.trycloudflare.com                                                    |
+--------------------------------------------------------------------------------------------+
now DONT run proxy.py
install this repository as zip, extract it, open file location and type in the location bar "cmd"
you should get a cmd that directs to that location
!!!MAKE SURE YOU HAVE PYTHON INSTALLED!!!
run in cmd "pip install opencv-python mss sounddevice numpy flask"
wait for everything to be installed
run in cmd "python server.py"
wait till it says "press ctrl+c to disconnect"
you may see your mouse flickering (but thats fine)
i will shortly upload MainModule2.rbxm, thats my current module to live stream
if u see ports named 5000 instead of 8000, rename them into 8000
upload MainModule2 to roblox
now REMEMBER that quick tunnel url? u need it now, copy and paste ur quick tunnel link
make sure u have dev perms in the game ur gonna use this and gave permissions (roblox feature) in the game to use it
require(game.InsertService:LoadAsset(YOUR MODULE URL HERE!):children''[1])('YOUR USERNAME HERE!','YOUR QUICK TUNNEL HERE!')
it will take some time to load in and will still have bugs, audio is buggy and doesnt work properly so i dont reccommend enabling it
