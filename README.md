# Overview

This is a scaffold for the redress extension. The code scaffold is based on https://github.com/bradtraversy/traversy-launcher, although I don't expect the scaffold code to stay unchanged for long.

Big picture structure:
1. All of the code for the chrome extension goes in the ``src`` folder, which stands for source. Inside the src folder we have:
	a. The manifest.json file declares to Google the main "metadata" about the extension, for example its title and purpose and the permissions it requires.
	b. The popup.html file contains the html (and some css) to generate the popup
	c. The popup.js file is empty but could contain javascript for the popup to make it interactive 
	d. The assets folder contains bits and pieces that make the extension look good. For example, icon images, fonts and formatting, etc.

# How to test the Extension

1. Go to chrome://extensions/, or alternatively:
	a. Go to chrome and click the settings option (currently three vertical dots.)
	b. Click "more tools"
	c. Click "Extensions"
2. When taken to the extensions page:
	a. Make sure developer mode is checked
	b. Make sure 


# Resources for Mich

1. Git and Github (used to share code): Sections 3.1-3.3 of https://amspector100.github.io/packageguidelines/version-control.html#setting-up-gitgithub

2. HTML/CSS (the stuff we use to build the visual part of the extension): https://internetingishard.com/html-and-css/introduction/

3. Example of a simple chrome extension: https://www.youtube.com/watch?v=wHZCYi1K664 

4. Example of a complicated chrome extension: https://github.com/cnwangjie/better-onetab/blob/master/src/manifest.json

5. Chrome web permissions: https://support.google.com/chrome/a/answer/7515036?hl=en 
We are going to have to think through which we need