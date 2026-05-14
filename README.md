# EDGE_AI

🔷 What is Edge AI?

Edge AI means running artificial intelligence directly on a device (microcontroller/edge device) instead of sending data to the cloud.

👉 In simple words:
AI runs inside device itself (like ESP32-S3), not on the internet.

| Feature    | Cloud AI                | Edge AI      |
| ---------- | ----------------------- | ------------ |
| Processing | Internet server         | Local device |
| Speed      | Slower (needs internet) | Very fast    |
| Internet   | Required                | Not needed   |
| Privacy    | Less secure             | More secure  |


### INSTALLATION

#### 1. Nodejs

* Open https://nodejs.org/en/download
* Choose version v22.22.2(LTS)
* node-v18.20.8-x64.tmsi
* Download & install

#### 2. Visual Studio Build Tool

* Open https://www.techspot.com/downloads/downloadnow/7493/?evp=1be7e1eb826c379157ad003b22469701&file=10391
* Install version 2022(v17)

#### 3. Edge Impulse

* Open https://www.edgeimpulse.com/
* Create an account with password


#### 4. Command Prompt

Frist you need to check whether vs build tool,node.js installed properly

* Open windows powershell
* Type "node -v"
* Type "npm -v"
* Type "npm install -g edge-impulse-cli"
* Type "edge-impulse-daemon"
* Type "edge-impulse-data-forwarder --frequency 1"
* Input Username & Password

  If not worked

==> Uninstall broken global install:

npm uninstall -g edge-impulse-cli

==> Clear npm cache:

npm cache clean --force

==>Reinstall:

npm uninstall -g edge-impulse-cli


Now everything install and we can start our first project

