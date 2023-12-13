# A VS Code Processing Java Template

This provides a minimum template to get Java Processing set up with visual studio code, the best dang coding editor out there! It also provides the option of using the online cloud editor Gitpod, which will be slower but will also work in any modern web browser.

## Getting Started with VS Code

### Install Dependencies

Before you can use this locally, you need to install Visual Studio Code, the Java Developer Kit, and a bunch of extensions. You have two pathways forward, pick whichever you prefer

#### Install everything in one go (easiest)

Microsoft provides a downloader that will help you install everything you need. This is probably the easiest option:

[Click here if you have a Mac!](https://aka.ms/vscode-java-installer-mac)

[Click here if you have a Windows PC!](https://aka.ms/vscode-java-installer-win)

#### OR Install everything manually

If you want to go this route, you'll need to install all three things below.

1. [Visual Studio Code](http://code.visualstudio.com) - The editor where we will type code

2. [Visual Studio Code Java Extension Pack](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack) - Installs more complete java support inside of visual studio code

Once the extension pack is installed, you can use the java tools in Visual Studio Code to install your java JDK, which is necessary to run the code. It should hopefully prompt you when the time comes! I recommend java version 17, that latest LTS version as of this writing.

### Download this project

You can download this project using the green "Download" button up above. If you have git installed, feel free to use it, but if not you can simply download the entire project as a ZIP file. Save it somewhere on your computer you can find it and won't delete it (maybe a special folder for code?) and extract the file by double-clicking.

### Open the project

Open Visual Studio Code, and click the "Open Folder" link on the main page, or use File->Open Folder. Navigate to the folder you just extracted, select it, and click Open.

It may take a minute to open the file, enable all the java extensions, and read in all of the dependencies. 

### Try running the project

Open the `Sketch.java` file, which is inside the `src` folder, then press `F5` or choose Run->Start Debugging . You should get a window with a circle and as you drag your mouse around it draws new circles!

You are ready to start tweaking the code in `Sketch.java`. Good luck!

## Alternative Pathway using Gitpod

Go to the top of this screen, where the address is, and add `https://gitpod.io/#` BEFORE the address of this template. Wait a few minutes and a full copy of this code should open in the cloud for you. You can run the code as above and use the VNC viewer in port 6080 (see the Ports menu) to access the visuals.