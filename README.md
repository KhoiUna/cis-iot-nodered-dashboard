# CIS IoT Dashboard using [node-red](https://nodered.org/)

- Node-RED flow editor [here](https://nodered.khoiuna.info/)

## Instructions
1. `npm i -g node-red` to install node-red globally
2. `npm i` to install local packages
3. `node-red admin init` to create your `settings.js` file with your own username and password (this will automatically secure your node-red editor. Read more about securing Node-RED [here](https://nodered.org/docs/user-guide/runtime/securing-node-red#generating-the-password-hash))
4. `node-red cis-iot.json -s settings.js` to start your **node-red** using your `settings.js` file
5. You might install `node-red-dashboard` by pressing `Alt + Shift + P` to bring up the `User Settings` then click on the `Install` tab and search for `node-red-dashboard`. Click `install`.
