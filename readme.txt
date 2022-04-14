
setup for https://github.com/simondevyoutube/Quick_3D_MMORPG


npm run start = web version
npm run start:electron = regular electron version
npm run start:electron-forge = electron forge cli managed version (good to use for publishing, thanks slack)

todo:
tests with floss (thanks pixi team / netflix)

notes: 

[20160:0414/095438.668:ERROR:interface_endpoint_client.cc(659)] Message 3 rejected by interface blink.mojom.Widget
electron throwing this error recently. (mojo is the rendering ipc layer 
kind of between web content and the main chrome process (not main electron process) )

