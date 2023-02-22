![DS1](https://static.wixstatic.com/media/d1a115_682f71ff537c4de9bb88be12c0ac4369~mv2.jpg/v1/fill/w_399,h_134,al_c,q_80,usm_0.66_1.00_0.01,enc_auto/Copy%20of%20DS%20Logo%20JPEG_edited.jpg)

# DS1-test-harness
Emulate DS1 CAN Websockets

## Usage
1. Execute ws.py
1. Connect to localhost:9997 with a websocketclient
1. send "ds2start" over the web socket
1. onMessage in your client will be invoked, the binary version not the text one.

## Limitations

I only captured one Frame of binary data on the 1st raster group (there are two, for sampling different values at different rates)

However, it would be very easy to capture more and add them if you desire. Just use DevTools to monitor the WebSocket after hitting "start" on the Data tab.


## Support

There is none except what I and other community members provide. 

### *DO NOT CONTACT DYNOSPECTRUM FOR SUPPORT*

These apis are not documented and subject to breaking changes at any time.
