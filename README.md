Chrome-Shortcut-Template
========================

  A template for installing a Chrome App as shortcut to your
  favorite site.

  [DEMO] (https://github.com/joshgo/Chrome-Shortcut-Template/blob/master/demo.png)

### Files

  * 128.png       - Chrome App icon template to display on the start page
  * manifest.json - Manifest template


### Configuring/Customizing

  OPTIONAL: Copy the files to a new directory 

  1. Replace the file 128.png with your image to represent the site/app

  2. Update the manifest.json file
     * Set the name/description
     * Replace http://github.com in **apps.urls** and in **apps.launch.web_url**

     
### Installing

#### By referencing app directory

NOTE: These steps will require your directory to exist after installation. Use pack extension for persistence.

  1. Go to **chrome://extensions**
  2. Click on "Developer Mode"
  3. Click "Load unpacked extension" 
  4. Select the directory that contains the manifest

#### By installing packed extension (.crx)

  1. Go to **chrome://extensions**
  2. Click on "Developer Mode"
  3. Click on "Pack Extension"
  4. Select the directory that contains the manifest (Extension Root Directory)
  5. Click OK (twice)
  6. Drag drop the .crx file (On **chrome://extensions** page)

NOTE: **Developer Mode** does need to be checked for the last step.
