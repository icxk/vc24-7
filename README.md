# vc24-7
pkg upgrade && pkg update
pkg install python -y
cd vc24-7
pip install - requirements.txt
nano main.py
python main.py

# setting
GUILD_ID = "server id"
CHANNEL_ID = "Voice channel id"
usertoken = "yourtoken"
ctrl + x + y


# how to get token
1. login discord account in browser
2. click search botton
3. paste javascript:(webpackChunkdiscord_app.push([[''],{},e=>{m=[];for(let c in e.c)m.push(e.c[c])}]),m).find(m=>m?.exports?.default?.getToken!==void 0).exports.default.getToken()
