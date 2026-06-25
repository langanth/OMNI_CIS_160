# IDE Setup Assignment

For this assignment you will be setting up your development environment for the semester. While working on this assignment, it is strongly recommended you watch the **Python Setup** video prior to working on this assignment. The information in that video correlates heavily with this assignment and it would be in your best interest to have it open for reference. Please follow the steps below and be sure to open up the important links below to help you with installing Python and Visual Studio Code. Please keep in mind that these steps may be different depending on your operating system. If you run into any issues, please do not hesitate to reach out to your instructor.

## Important Links
- [Python Download](https://www.python.org/downloads/)
- [Visual Studio Code](https://code.visualstudio.com/)

## Part 1
Before actually working on the assignment itself, you will need to install both Python and Visual Studio. Part 1 will walk you through how to install Python.

1. Navigate to [Official Python](https://www.python.org/downloads/) website and download the latest version of python. For simplicity, do not download the python install manager. Instead download the stand alone installer for the current stable version of python.

> 	Please note that the contents of this course rely on students using a python version of 3.11 or newer. If you choose to run a different version of python than the current stable version you may do so as long as it is newer than 3.11.

2. Locate the file you just downloaded (most likely in your downloads folder) and double click on that file.
3. The installer will begin to run.
4. Ensure that you check the boxes for installing with admin privileges and adding the python.exe to path.

![python_install](/images/python_install.png)

> 	Not adding the python.exe to path may lead to problems later when trying to use certain features.
	
5. Continue through the installation until it is complete.

## Part 2
In this part you will be installing Visual Studio Code.

1. Navigate to [Visual Studio Code](https://code.visualstudio.com/) and download the installer.
2. Locate the file you just downloaded and double click on it to begin the installation.
3. Accept the EULA and select **next**.
4. Ensure that the Add to PATH and register Code as an editor for supported files and click next.

![vscode_installer](/images/vscode_installer.png)

5. Finish the installation.

## Part 3
Part 3 will walk you through setting up a project folder to hold your files for this course. In addition, this will walk you through setting up VS Code in a way to work with python.

1. Create a folder on your computer at a location that you can easily access. Name the folder "CIS_160". We will use this as a place to organize all of our files for this assignment and potentially the course.
2. Open up **Visual Studio Code** and look for the extensions tab on the left hand side. Its icon is depicted below. Click on it and in the search bar, type in python.

![extensions_icon](/images/extensions_icon.png)

3. Click on the Python extension by Microsoft and install it. It should look like the image below.

![python_extension_icon](/images/python_extension_icon.png)

4. Go ahead and close the tab it opened after it is done installing.
5. Next you will need to open the folder you created. This will be your project folder moving forward. Click on **File** and then click on **Open Folder...** which will then open up a new window. Locate your folder and click select folder. If you are on a Mac, you will click on the apple icon in the top left and click on **Open Folder...** as well and then locate the folder you created, select it and click on select folder.
6. This will open the folder in Visual Studio Code and you can now modify its contents. Hover over the explorer window and you will see some new icons appear in the window. Click on the icon that looks like a piece of paper with the corner folded over and a plus sign on it.

![explorer_icon](/images/explorer_icon.png)

7. This will create a new file where a text box will be open and expecting you to type in a name for the file. type in `hello_world.py` and press enter.
![hello_world](/images/hello_world.png)

> 	You have now created a new python file. Adding `.py` after any text when creating a file will automatically create the file as a python file.

8. The `hello_world.py` file will be displayed in the main window now. Here you will write the code below and be sure to replace `Cassian Andor` with your name instead.

```
msg = "Hello world!"
print(msg)
name = "Cassian Andor"
print("My name is", name)
```

9. Once you have written your code, we will now run the python file for testing. On the upper right hand side of the window you will see a triangle point to the right. This is the run button. Press that button to run the python script. It may produce a dropdown menu, click on the **Run Python File**.
10. Take a screen shot of the results and place the image in a word document and submit it to Blackboard. The final results should look similar to the following:

![result](/images/result.png)
