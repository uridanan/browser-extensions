This project is a chrome extension that invokes the Clipperz Delta interface inside a chrome extension popup (using an iframe).
At this point this extension does not include persistent login, which means you have to enter your credentials each time you invoke the extension.
I'm hoping to find a way around this problem to make this extension really useful.

I copied the procedure below from the clipperz-chrome-extension project. 

To verify that extension works use this steps (as per http://code.google.com/chrome/webstore/docs/get_started_simple.html#step4):
 - Bring up the extensions management page by clicking the wrench icon and choosing Tools > Extensions.
 - If Developer mode has a + by it, click the +.
 - The + changes to a -, and more buttons and information appear.
 - Click the "Load unpacked extension" button.
 - A file dialog appears.
 - In the file dialog, choose the "clipperz-chrome-extension" directory.

To archive extension for deployment you can simply use Google Chrome.
Open extensions management page in Developer mode as described above and click "Pack extension" button.
Please refer this link for details: http://code.google.com/chrome/extensions/packaging.html.