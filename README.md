# QUARCS_README

![样机-1 2](https://github.com/QHYCCD-QUARCS/QUARCS_stellarium-web-engine/assets/158538628/1fdb2fc3-7b6b-42fb-ba9e-bc4cf6f613a1)
![样机-2 2](https://github.com/QHYCCD-QUARCS/QUARCS_stellarium-web-engine/assets/158538628/7ad24990-f259-4396-bb94-e56f6f94abc3)

Q.U.A.R.C.S  (QHYCCD Universal Astrophotographic Remote Capture System) is an open-source software kit that supports the full function of mobile remote capture via WIFI and computer remote capture via LAN. It includes the mount control, camera control, autoguiding, electric focuser control, and Stellarium skymap function. 

The QUARCS includes the following parts

-- QUARCS server. It is the hardware control server, written with QT. This server uses the INDI library to control the astronomy hardware. 

-- Modified PHD2 guider. We modified the PHD2 guide to get better communication with the QUARCS server.

-- QUARCS user client frontend. It is based on the stellarium web edition, which is a Vue frontend. We add the image capture function, device connection function, autoguider control and curve function, histogram function, capture planner table function, etc. 

-- QUARCS app. Which is a simple QT framework for the mobile app.  It supports Android (the IOS version is also under development) The app has a built-in browser to support the frontend display. And it has an IP address detector function to find the server automatically. 

-- QUARCS node js Transponder. Which is a websocket packet forwarding/transponder server. All the communication between the QUARCS server and the client is going through it.  It also manages the server/client's online and offline events.


The QUARCS installation

I'd like for you to follow this sequence to install the whole project. Please follow the README.MD in each part. The installation is tested under the empty Ubuntu22.04

1. QUARCS server.
2. Modified PHD2 guider
3. QUARCS user clinet frontend (Stellarium web edition)
4. QUARCS node js Transponder
5. QUARCS app


Welcome to join the QUARUS Discod discussion group for online discussions (https://discord.gg/uHTPfJ5uuV)
