Game not loading? Issues running it in your browser? Here's some things you can do:
## If you're running on Chrome:
1. Go to get.webgl.org to check if you have WebGL enabled in your browser. If it is enabled, you should see a spinning cube on the webpage. If not, please continue to step 2.
2. Go to chrome://settings in your browser.
3. Click the Show advanced settings… link at the bottom of the page.
4. Scroll down to the System section and make sure the Use hardware acceleration when available checkbox is checked.
- If this is not checked, this is most likely the cause of your issue; click on the checkbox and restart Google Chrome. Please check Eiger to see if the issue is resolved. If issues persist in Eiger, please continue to step 5.
5. Go to chrome://gpu.
6. Navigate to the Graphics Feature Status section. WebGL will have a status of one of the following:
- Hardware accelerated: WebGL is enabled and hardware-accelerated (running on the graphics card).
- Software only, hardware acceleration unavailable: WebGL is enabled, but running in software only.
- Unavailable: WebGL is not available in hardware or software.
7. If the WebGL status does not state Hardware accelerated, navigate to the Problems Detected section for further explanation. WebGL may be unavailable due to following reasons:
- An extension in Google Chrome is disabling WebGL from being used.
- The current version of your graphics driver needs to be updated to the latest version.
- Your computer's graphics card / driver is blacklisted with the latest version of Google Chrome. Go to https://threejs.org/examples/#webgl_animation_cloth to see if your hardware is compatible with running WebGL.

_(credits to support.markforged.com)_

## If you're running on Edge:

Enable WebGL status
In an Edge browser window, type edge://settings/system in the URL field.

Ensure that "Use hardware acceleration when available" is checked. If you need to check it, be sure to restart your browser afterward so the change takes effect. 

Check WebGL status
Next, go to edge://gpu

Under the "Graphics Feature Status" list, find WebGL to learn its status. 

If it says "Hardware accelerated" then WebGL is running on the graphics card.

If the status is not "Hardware accelerated", then the Problems Detected list (below the the Graphics Feature Status list) may explain why hardware acceleration is unavailable. 

If "B" is your outcome, you should contact our Help team. Please provide us with a GPU report from step 4 above—by opening a window in Chrome and typing chrome://gpu into your address bar. Copy and paste the report into the email. 

_(credits to picmonkey.com)_