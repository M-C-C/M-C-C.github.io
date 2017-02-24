# System requirements
OS: Windows 7/8/8.1/10 64-bit or 32-bit
RAM: 2GB
Free HD Space: 8GB

# Windows Install instructions
1. Find out if your system is running 64-bit or 32-bit
Windows 8/8.1/10: hit the windows key and type in `This PC`, right click on `This PC` and click `Properties`
Windows 7: hit the windows key and type in `computer`, right click on `computer` and click `Properties`

You may need to scroll down to find it. there should be a line saying `System Type: ` with something that says 64-bit OS or 32-bit OS
2. Download and run Node.js Installer
  - https://nodejs.org/dist/v7.6.0/node-v7.6.0-x64.msi
3. Download and install Git
4. Download and run the Ruby Installer
  - (64-bit) https://dl.bintray.com/oneclick/rubyinstaller/rubyinstaller-2.3.3-x64.exe
  - (32-bit) https://dl.bintray.com/oneclick/rubyinstaller/rubyinstaller-2.3.3.exe
5. Download the Ruby DevKit
  - (64-bit) https://dl.bintray.com/oneclick/rubyinstaller/DevKit-mingw64-64-4.7.2-20130224-1432-sfx.exe
  - (32-bit) https://dl.bintray.com/oneclick/rubyinstaller/DevKit-mingw64-32-4.7.2-20130224-1151-sfx.exe
6. Open the application, a prompt will pop up asking where to extract the files. Make a new folder in the C:/ drive called `Ruby-DevKit`.
   Click that folder to select it and click ok. This will take quite a bit depending wether you are running Windows on a Solid-State-Drive
   or a Hard Disk Drive
7. Open command prompt by pressing `Ctrl-R` and typing `cmd` into the input field
8. Type the following commands:
```
cd C:/Ruby-DevKit
ruby dk.rb init
ruby dk.rb install
exit
```
9. Command prompt will close, open it again and type the following commands:
```
git clone https://github.com/m-c-c/m-c-c.github.io
cd m-c-c.github.io
npm install
```
Optional: Change the folder name to your repository (replace your-fork-name with your repositories name and replace your-fork-url with your repositories URL)
```
git clone https://github.com/m-c-c/m-c-c.github.io -o your-fork-name
cd your-fork-name
git remote set-url origin your-repository-url
npm install
```
If you see a thumbs up when running `npm install` then you are pretty much set to work on glixer!


