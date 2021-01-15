# obsidian-inbox
An Android App for Android which will read and update a dropbox text file. Developed using MIT App Inventor 2 (https://appinventor.mit.edu/)

The specific file I needed to access and update is a markdown file in my obsidian vault which is kept in dropbox.

I built this app in a couple of hours using MIT App Inventor 2 (see step 4 below) which is great for quickly building Android Apps without all the hassle of Java and the Android SDK.

## Pre-requisites
1. A dropbox account
2. A dropbox Access Token for the App - see http://99rabbits.com/get-dropbox-access-token/
3. Take note of the folder that dropbox sets up within its Apps folder this is your root folder for the app
4. MIT App Inventor 2 Account (easy to set up and free) by going to https://appinventor.mit.edu/ and clicking Create Apps button

## Customising the app
A. Click start a new project
B. Download the file *obsidian_inbox.aia.zip* to your computer
C. Choose Projects menu, Import project (.aia) from my computer and choose the file *obsidian_inbox.aia* you just unzipped in step A
D. Once the project is loaded click on the Blocks button at the top right (see file *obsidian_inbox_blocks.pdf* for image of the blocks
E. change the global variables as follows
F. global DropboxAccessToken   - set to your Dropbox Access Token value
- global DropboxFolder - folder location of the text file - relative to the root folder of your Dropbox Apps - see 3 above
- global DropboxFilename - name of the text file - in my case it is my obsidian input markdown file *00 - Input.md*
G. Now the app with your settings is ready to be tested, the options are
- use the Companion App which will test your app on your phone - see https://appinventor.mit.edu/explore/ai2/setup-device-wifi.html
- use the MIT App Inventor Emulator which you will need to download - see https://appinventor.mit.edu/explore/ai2/setup-emulator.html
- or save the project as an installable file (.apk) which you can manually install on your Android phone and test it.

## Using the App
Click the Inbox Button and text file is retrieved, edit text as required and click update to save changes to dropbox.

## Next Steps
Hopefully this project can be useful to obsidian users and if you get familiar with MIT App Inventor 2 then it would be easy to customise this basic app further with ideas such as
- Dropdown list of multiple text files you may wish to update
- add a markdown preview screen
- add voice input and/or text to speech
etc

