# How To Install Python 3 on Windows 

### Introduction
Python is a widely used high-level programming language first launched in 1991. Since then, Python has been gaining popularity and is considered as one of the most popular and flexible server-side programming languages.

Unlike most Linux distributions, Windows does not come with the Python programming language by default. However, you can install Python on your Windows server or local machine in just a few easy steps.

<p align="center">
<br>
  <a href="https://github.com/System-Zombiesx/Hello-world-challang-python.git"><img src="https://i.imgur.com/0TcDpFf.png" alt="ZHunter"></a>
 <br>
  </p>
  
### Prerequisites
* A system running Windows 10 with admin privileges
* Command Prompt (comes with Windows by default)
* A Remote Desktop Connection app (use if you are installing Python on a remote Windows server)
  
### Step 1: Select Version of Python to Install
The installation procedure involves downloading the official Python .exe installer and running it on your system.

The version you need depends on what you want to do in Python. For example, if you are working on a project coded in Python version 2.6, you probably need that version. If you are starting a project from scratch, you have the freedom to choose.

If you are learning to code in Python, we recommend you download both the latest version of Python 2 and 3. Working with Python 2 enables you to work on older projects or test new projects for backward compatibility.
### Step 2: Download Python Executable Installer
1. Open your web browser and navigate to the [Downloads for Windows section ](https://www.python.org/downloads/windows/)of the [official Python website](https://www.python.org/)
2. Search for your desired version of Python. At the time of publishing this article, the latest Python 3 release is version 3.7.3, while the latest Python 2 release is version 2.7.16.
3. Select a link to download either the Windows x86-64 ***executable installer*** or ***Windows x86 executable installer***. The download is approximately 25MB.

<p align="center">
<br>
  <a href="https://github.com/System-Zombiesx/Hello-world-challang-python.git"><img src="https://i.imgur.com/CGPkQq1.png"></a>
 <br>
  </p>
  
### Step 3: Run Executable Installer

1. Run the Python Installer once downloaded. (In this example, we have downloaded Python 3.7.3.)
2. Make sure you select the ***Install launcher for all users*** and ***Add Python 3.7 to PATH*** checkboxes. The latter places the interpreter in the execution path. For older versions of Python that do not support the Add Python to Path checkbox
3. Select ***Install Now*** – the recommended installation options.

<p align="center">
<br>
  <a href="https://github.com/System-Zombiesx/Hello-world-challang-python.git"><img src= "https://i.imgur.com/KSpgo6Q.png"></a>
 <br>
  </p>

For all recent versions of Python, the recommended installation options include ***Pip*** and ***IDLE***. Older versions might not include such additional features.

4. The next dialog will prompt you to select whether to ***Disable path length*** limit. Choosing this option will allow Python to bypass the 260-character MAX_PATH limit. Effectively, it will enable Python to use long path names.

<p align="center">
<br>
  <a href="https://github.com/System-Zombiesx/Hello-world-challang-python.git"><img src="https://i.imgur.com/QLnHhIX.png"></a>
 <br>
  </p>

The ***Disable path length*** limit option will not affect any other system settings. Turning it on will resolve potential name length issues that may arise with Python projects developed in Linux.

### Step 4: Verify Python Was Installed On Windows 

1. Navigate to the directory in which Python was installed on the system. In our case, it is ***C:\Users\Username\AppData\Local\Programs\Python\Python37*** since we have installed the latest version.
2. Double-click ***python.exe.***
3. The output should be similar to what you can see below:

<p align="center">
<br>
  <a href="https://github.com/System-Zombiesx/Hello-world-challang-python.git"><img src="https://i.imgur.com/ga7zh6Z.png"></a>
 <br>
  </p>
  
### Step 5: Verify Pip Was Installed

If you opted to install an older version of Python, it is possible that it did not come with Pip preinstalled. Pip is a powerful package management system for Python software packages. Thus, make sure that you have it installed.

We recommend using Pip for most Python packages, especially when working in virtual environments.

To verify whether Pip was installed:
1. Open the ***Start*** menu and type ***"cmd."***
2. Select the ***Command Prompt*** application.
3. Enter ***pip -V*** in the console. If Pip was installed successfully, you should see the following output:

<p align="center">
<br>
  <a href="https://github.com/System-Zombiesx/Hello-world-challang-python.git"><img src="https://i.imgur.com/YTg3xmC.png"></a>
 <br>
  </p>
  
Pip has not been installed yet if you get the following output:
```
'pip' is not recognized as an internal or external command,
Operable program or batch file.
```

### Step 6: Add Python Path to Environment Variables (Optional)

We recommend you go through this step if your version of the Python installer does not include the Add Python to PATH checkbox or if you have not selected that option.

Setting up the Python path to system variables alleviates the need for using full paths. It instructs Windows to look through all the PATH folders for “python” and find the install folder that contains the python.exe file.

1. Open the ***Start menu*** and start the ***Run*** app.

<p align="center">
<br>
  <a href="https://github.com/System-Zombiesx/Hello-world-challang-python.git"><img src="https://i.imgur.com/n4NWoi5.jpg"></a>
 <br>
  </p>
  
2. Type ***sysdm.cpl*** and click ***OK***. This opens the ***System Properties*** window.
3. Navigate to the ***Advanced*** tab and select ***Environment Variables.***
4. Under System Variables, find and select the Path variable.
5. Click ***Edit.***
6. Select the ***Variable value*** field. Add the path to the ***python.exe*** file preceded with a ***semicolon (;)***. For example, in the image below, we have added ***";C:\Python34."****

<p align="center">
<br>
  <a href="https://github.com/System-Zombiesx/Hello-world-challang-python.git"><img src="https://i.imgur.com/CXvSz0h.png"></a>
 <br>
  </p>
  
7. Click ***OK*** and close all windows.

    
