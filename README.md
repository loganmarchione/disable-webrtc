# This extension is no longer maintained.

# Disable WebRTC
WebExtension that disables WebRTC  
  
To ensure your IP address does not leak while using a VPN (or another IP-masking technology), this extension disables WebRTC in Firefox 57+ by using the new API for browser.privacy.network.peerConnectionEnabled  
https://developer.mozilla.org/en-US/Add-ons/WebExtensions/API/privacy/network  
  
Confirm the setting with the URL below. It should be set to "false".  
about:config?filter=media.peerconnection.enabled  
  
## Available for Firefox

[![Mozilla Add-Ons](https://raw.githubusercontent.com/loganmarchione/disable-webrtc/master/icon_firefox_amo.png)](https://addons.mozilla.org/en-US/firefox/addon/disable-webrtc/)
