# JavaScript Code Editor

This is just a simple JavaScript code editor that I made where you can create files, write code, and run it in the browser. It is heavily inspired by [Replit.com](https://replit.com)'s IDE.
## Build Instructions

Now, this does require Node.js and npm to be installed on the computer beforehand, but if you're wanting to build this program on your computer, then I would suspect you've already got the tools ready to go. But just in case you don't, [here is the website link for Node.js which has a download link](https://nodejs.org). npm is also included. Unfortunately, since I use Windows only, I only have instructions for Windows 10 and 11 here, so if you have a macOS computer and don't know how to extract a folder, there are plenty of great tutorials online to help you do that, I'd suggest going on [Google](https://google.com) and searching for them.

1. **Go to the `js-editor.zip` file and download it** - it should be above this tutorial. Click on it, then click the "Download raw file" button with the download icon on it. This should download the file to your computer.
2. **Extract the compressed folder** - Go to the location of the file. There should be a button to do it in the "Downloads" region of your browser, next to the file name. Next, you need to extract the file. On Windows, you have to right-click the `js-editor.zip` file, and click "Extract All..", and then at the bottom of the popup window that appears, click "Extract." This should create and open a new regular folder with a lot of files inside.
3. **Open the folder and open the terminal** - Once the folder has opened, right-click while holding the <kbd>Shift</kbd> key, and open the "Open PowerShell window here" button which will open a window in PowerShell.
4. **Install the modules and run the editor** - In PowerShell, first run the command `npm install` and wait for the packages to update. Once it is done, run `npm run dev`, which should run Vite, the build tool that I used to develop the code editor.
5. **See my work** - Finally, open a new browser tab and enter "http://localhost:5173/" into the Omnibox. This should open the code editor page, and congratulations! You have sucessfully built my code editor! Enjoy coding!
