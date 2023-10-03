Goal: Replace Post request "Aqara Home" app on HomeAssistant

-  this flow is example and was developed for Aqara Hub G3 camera

---

- Requirement:

NodeRed on HomeAssistant

NodeRed Companion on HomeAssistant

Palette "node-red-contrib-config" for NodeRed

Access internet from HomeAssistant server (for aqara URL https)

Aqara 4.0.2_mod_network.apk or Aqara 3.0.6_mod_network.apk

( https://drive.google.com/file/d/1Wfn_ynyCGvPwldjbbNGvZmYBKj5csuMy/view?usp=sharing )

---

- Requirement for find your data on BurpSuite software:

Install BurpSuite https://github.com/SNGWN/Burp-Suite

Install “Aqara Home” mod network apk on Android Phone

Install your certificate BurpSuite on Android Phone

Set proxy on Android Phone wifi with IP PC BurpSuite

---

- Find your value from BurpSuite, replace into “config" node into NodeRed:

appid	(XXXXXXAPPIDXXXXXXXXXXX)

userid	(XXXXXXUSERID.USERIDXXXXXXXXXXX)

token	(XXXXXXTOKENXXXXXXXXXXX)

aqara_url	(example EU = rpc-ger.aqara.com )

lumi1.54ef443a120c (example for Aqara G3 EU)

---

- Result

![immagine](https://github.com/sdavides/AqaraPOST-Homeassistant/assets/31100253/92e05aa3-8dd3-4257-9c3b-ccc84f4e65d8)
![immagine](https://github.com/sdavides/AqaraPOST-Homeassistant/assets/31100253/316750b5-7ddb-4539-a2b8-c157d262215c)

