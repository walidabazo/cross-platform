
cross-platform you Can be used (JavaScript, HTML, , CSS, Sqlite)
We Will working same code on website, desktop application(windows - macOS - Linux) and mobile app (Android - IOS)
Large company in world used it such as Visual Studio Code, WhatsApp,Twitch,Microsoft Teams ,InVision , facebook messenger , .....


### how to Start Create Your application by (JavaScript, HTML, , CSS and Sqlite)

# To Building on desktop application(windows - macOS - Linux) we Will Used electron-packager

 ### Supported Platforms
Electron Packager is known to run on the following host platforms:

Windows (32/64 bit)
macOS (formerly known as OS X)
Linux (x86/x86_64)
It generates executables/bundles for the following target platforms:

Windows (also known as win32, for x86, x86_64, and arm64 architectures)<br/>
macOS (also known as darwin) / Mac App Store (also known as mas)* (for x86_64 and arm64 architectures)<br/>
Linux (for x86, x86_64, armv7l, arm64, and mips64el architectures)<br/>

* Note for macOS / Mac App Store target bundles: the .app bundle can only be signed when building on a host macOS platform.

 ### Installation electron-packager
 1- Download and install Node.js 10.0 or higher https://nodejs.org/en/
   <br/>2- Download electron-packager https://github.com/electron/electron-quick-start
   <br/>3- Open run and CMD 
   <br/>  # install NPM
  
     npm install
     npm install electron-packager -g 
 ### if You can Be Add SQlite in your Application will working Done with electron-packager
      npm install sqlite --save
      OR
      npm install sqlite@3 --save
<br/> 4-Main.js very important (Modules to control application life and create native browser window)
     Can be change (loadFile - Screen size - X, Y , window or multi windows) 
   
  <br/> 5- package.json (This for application information) app name , version , description.
   <br/><br/> 6-Build your Project 
    <br/>A) Without encryption code and default icon app       
           
           electron-packager <sourcedir> <appname> --platform=<platform> --arch=<arch> myapp-source-built
           //Such as
           //electron-packager E:\Test\Soc test_app  --platform=win32 --arch=x64 myapp-source-built
 <br/>   B) With encryption code and your icon app   
   
       electron-packager E:\Test\Soc --overwrite --asar=true --platform=win32 --arch=x64 --icon=E:\Test\Soc\e.ico --prune=true --out=release-builds --version-string.CompanyName=walidabdelazeem --version-string.FileDescription=CE --version-string.ProductName="Electron Tutorial App"
 
## Good Company hosting and low price VPN 
https://shorturl.edafait.com/?fZVHLor
           
