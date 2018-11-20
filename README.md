# miner-monitor
miner-monitor
Prerequisites
miner-monitor requires nodejs >= 8.9.0, npm and optionally pm2 to run.

miners require the miner-manager to be installed

Installation
Open miner-monitor
npm install
npm install pm2 -g
Run
pm2 start process.json
or

npm start
to startup on boot:

pm2 save
pm2 startup
If you are on Windows just modify startTemplate.bat file to match your preferred compile and save as start.bat to not interfere with git updates

Update software
run git pull

Todos
Write Tests
License
GNU GPLv3 (see LICENSE)
