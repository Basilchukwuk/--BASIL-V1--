# --BASIL-V1--

Navigation Menu
Sign in
BASIL
/
V1
Public
 94 stars  374 forks  Branches  Tags  Activity
Code
Issues
1
--BASIL V1--
Folders and files
Name	
Latest commit
BASIL
BASIL
2 days ago
History
.github/ISSUE_TEMPLATE
3 weeks ago
lib
2 days ago
media
3 weeks ago
plugins
3 weeks ago
.gitignore
3 weeks ago
.replit
3 weeks ago
Dockerfile
3 weeks ago
README.md
2 weeks ago
app.json
3 weeks ago
config.js
2 weeks ago
heroku.yml
3 weeks ago
index.js
3 weeks ago
package.json
2 days ago
replit.nix
3 weeks ago
yarn.lock
2 days ago
Repository files navigation
README
WhatsApp MD User Bot
A simple WhatsApp User bot.

Setup
1. Deploy on Heroku
Scan QR Code:

Click SCAN and scan the QR code through the "WhatsApp Linked Devices" option in your WhatsApp app.
You will get a session ID in WhatsApp; copy the ID only.
Create Accounts:

If you don't have an account on Heroku, create an account now.
If you don't have a GitHub account, sign up now.
Fork Repository:

FORK this repository.
Deploy:

Now DEPLOY.
2. Deploy on Koyeb
Create an Account:

Create an account on Koyeb. Sign up now.
Get Required Information:

Get the DATABASE_URL. You'll need this while deploying.
Get the SESSION_ID. Open Linked Devices in WhatsApp and SCAN now.
Get the Koyeb API key. Let's Go.
Deploy:

Deploy to Koyeb
Enter Environment Variables. Read More.
Enter a name and click "Create Service."
3. Deploy on VPS or PC (Example here as in Ubuntu)
Install with Script
Run the following command:
bash <(curl -fsSL http://bit.ly/43JqREw)
Install without Script
Install Git, ffmpeg, and curl:

sudo apt -y update && sudo apt -y upgrade
sudo apt -y install git ffmpeg curl
Install Node.js:

curl -fsSL https://deb.nodesource.com/setup_20.x -o nodesource_setup.sh
sudo -E bash nodesource_setup.sh
sudo apt-get install -y nodejs
Install Yarn:

sudo npm install -g yarn
Install pm2:

sudo yarn global add pm2
Clone Repository and Install Packages:

git clone https://github.com/lyfe00011/levanter botName
cd botName
yarn install
Enter Environment Variables:

echo "SESSION_ID = Session_Id_you_Got_After_Scan_Dont_Add_This_Line_If_You_Can_Scan_From_Terminal_Itself
PREFIX = .
STICKER_PACKNAME = LyFE
ALWAYS_ONLINE = false
RMBG_KEY = null
LANGUAG = en
WARN_LIMIT = 3
FORCE_LOGOUT = false
BRAINSHOP = 159501,6pq8dPiYt7PdqHz3
MAX_UPLOAD = 200
REJECT_CALL = false
SUDO = 989876543210
TZ = Asia/Kolkata
VPS = true
AUTO_STATUS_VIEW = true
SEND_READ = true
AJOIN = true
DISABLE_START_MESSAGE = false
PERSONAL_MESSAGE = null" > config.env
Read More
Edit config.env Using Nano (if needed):

To save, press Ctrl + O, then press Enter, and to exit, press Ctrl + X.
Start and Stop the Bot:

To start the bot:
pm2 start . --name botName --attach --time
To stop the bot:
pm2 stop botName
4. Deploy on Replit
Run on Replit

Fork the repository.
Edit config.env.
Click run.
5. Deploy on Render
Create an Account:

Create an account on render. Sign up now.
Get Required Information:

Get the DATABASE_URL. You'll need this while deploying.
Get the SESSION_ID. Open Linked Devices in WhatsApp and SCAN now.
Get the render API key. Let's Go.
Deploy:

Deploy to Render
Thanks To
Yusuf Usta for WhatsAsena
@adiwajshing for Baileys
